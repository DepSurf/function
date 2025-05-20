# Function: <code>call_usermodehelper_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81096904)
Location: kernel/kmod.c:519
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:call_usermodehelper
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81096a90-ffffffff81096b28: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81099f05)
Location: kernel/kmod.c:519
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper
  - kernel/kmod.c:__request_module
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81099e50-ffffffff81099ee8: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109eeb5)
Location: kernel/kmod.c:519
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper
  - kernel/kmod.c:__request_module
Direct callers:
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8109ee00-ffffffff8109ee98: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109c1b5)
Location: kernel/kmod.c:536
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper
  - kernel/kmod.c:__request_module
Direct callers:
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8109c250-ffffffff8109c2e8: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a2eb5)
Location: kernel/umh.c:367
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810a2f50-ffffffff810a2fe8: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a9539)
Location: kernel/umh.c:374
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810a95b0-ffffffff810a9648: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b2429)
Location: kernel/umh.c:378
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b2660-ffffffff810b270c: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7fc9)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b8200-ffffffff810b82a6: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810be4c9)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810be700-ffffffff810be7a6: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c56a9)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:call_modprobe
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c5440-ffffffff810c54e6: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c09d9)
Location: kernel/umh.c:356
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:call_modprobe
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c0680-ffffffff810c0726: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c23d9)
Location: kernel/umh.c:358
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c2080-ffffffff810c2126: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810d4f19)
Location: kernel/umh.c:358
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810d4b60-ffffffff810d4c61: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810eded9)
Location: kernel/umh.c:358
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810edaf0-ffffffff810edc03: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8110f3a9)
Location: kernel/umh.c:359
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8110ef70-ffffffff8110f082: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8111b849)
Location: kernel/umh.c:356
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/module/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8111b410-ffffffff8111b522: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff81125346)
Location: kernel/umh.c:356
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/module/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81124ef0-ffffffff8112501e: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011ae60)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff80001011aa48-ffff80001011aaf4: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036f3cc)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c036f450-c036f4e4: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c000000000162fd8)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000162ea0-c000000000162f8c: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d540a)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0000d54a0-ffffffe0000d5544: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8839)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b8a70-ffffffff810b8b16: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a7179)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810a73b0-ffffffff810a7456: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7d99)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b7fd0-ffffffff810b8076: call_usermodehelper_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct subprocess_info *call_usermodehelper_setup(const char *path, char **argv, char **envp, gfp_t gfp_mask, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c0459)
Location: kernel/umh.c:379
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
Direct callers:
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c04d0-ffffffff810c0576: call_usermodehelper_setup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *path</code> ➡️ <code>const char *path</code>
</li>
</ul>
</details>
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
