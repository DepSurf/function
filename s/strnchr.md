# Function: <code>strnchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1a40)
Location: lib/string.c:422
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff813f1a40-ffffffff813f1a81: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438400)
Location: lib/string.c:422
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81438400-ffffffff81438438: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814553f0)
Location: lib/string.c:422
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff814553f0-ffffffff81455428: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f6eb0)
Location: lib/string.c:422
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - security/apparmor/lib.c:aa_splitn_fqname
  - net/core/dev.c:__dev_alloc_name
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff818f6eb0-ffffffff818f6ee8: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197d8b0)
Location: lib/string.c:423
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8197d8b0-ffffffff8197d8e8: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9db0)
Location: lib/string.c:423
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff819d9db0-ffffffff819d9de2: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a11fd0)
Location: lib/string.c:424
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a11fd0-ffffffff81a12002: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81490)
Location: lib/string.c:463
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a81490-ffffffff81a814b0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8560)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ab8560-ffffffff81ab8580: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f31a0)
Location: lib/string.c:506
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/integrity/ima/ima_template_lib.c:ima_show_template_field_data
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff815f31a0-ffffffff815f31c0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617850)
Location: lib/string.c:503
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/integrity/ima/ima_template_lib.c:ima_show_template_field_data
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81617850-ffffffff81617870: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815faed0)
Location: lib/string.c:503
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/integrity/ima/ima_template_lib.c:ima_show_template_field_data
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff815faed0-ffffffff815faef0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668780)
Location: lib/string.c:504
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/spi/spi.c:__spi_register_driver
```
**Symbols:**

```
ffffffff81668780-ffffffff816687a0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81781df0)
Location: lib/string.c:465
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/base/driver.c:driver_set_override
  - drivers/spi/spi.c:__spi_register_driver
```
**Symbols:**

```
ffffffff81781df0-ffffffff81781e24: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203ebb0)
Location: lib/string.c:400
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - drivers/base/driver.c:driver_set_override
  - drivers/spi/spi.c:__spi_register_driver
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8203ebb0-ffffffff8203ebe4: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd0c0)
Location: lib/string.c:400
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - drivers/base/driver.c:driver_set_override
  - drivers/spi/spi.c:__spi_register_driver
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff820bd0c0-ffffffff820bd0f4: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff821979c0)
Location: lib/string.c:385
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/bpf/verifier.c:check_reg_const_str
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/apparmor/lib.c:aa_splitn_fqname
  - drivers/base/driver.c:driver_set_override
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_cmdline_named_mode
  - drivers/spi/spi.c:__spi_register_driver
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff821979c0-ffffffff821979f4: strnchr (STB_GLOBAL)
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
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d929d0)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffff800010d929d0-ffff800010d92a00: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f110)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/integrity/ima/ima_template_lib.c:ima_show_template_field_data
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c0e8f110-c0e8f158: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6900)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c000000000ed6900-c000000000ed6934: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcab2)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffe0008bcab2-ffffffe0008bcad6: strnchr (STB_GLOBAL)
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
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a573b0)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a573b0-ffffffff81a573d0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14490)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a14490-ffffffff81a144b0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac37a0)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ac37a0-ffffffff81ac37c0: strnchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strnchr(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfc70)
Location: lib/string.c:465
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - mm/slub.c:kmem_cache_flags
  - fs/binfmt_script.c:load_script
  - security/security.c:security_setprocattr
  - security/apparmor/lib.c:aa_splitn_fqname
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81acfc70-ffffffff81acfc90: strnchr (STB_GLOBAL)
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
