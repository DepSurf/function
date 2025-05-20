# Function: <code>call_usermodehelper_exec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81096230)
Location: kernel/kmod.c:555
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:call_usermodehelper
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81096230-ffffffff81096396: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff810995f0)
Location: kernel/kmod.c:555
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - kernel/kmod.c:call_usermodehelper
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810995f0-ffffffff81099753: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109e5a0)
Location: kernel/kmod.c:555
Inline: False
Direct callers:
  - kernel/kmod.c:call_usermodehelper
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8109e5a0-ffffffff8109e703: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109bbf0)
Location: kernel/kmod.c:577
Inline: False
Direct callers:
  - kernel/kmod.c:call_usermodehelper
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8109bbf0-ffffffff8109bd61: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a28e0)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810a28e0-ffffffff810a2a57: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a9270)
Location: kernel/umh.c:526
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810a9270-ffffffff810a93e9: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b2160)
Location: kernel/umh.c:547
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b2160-ffffffff810b22d9: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7cf0)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b7cf0-ffffffff810b7e68: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810be1f0)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810be1f0-ffffffff810be368: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c54f0)
Location: kernel/umh.c:559
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:call_modprobe
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c54f0-ffffffff810c5668: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c0820)
Location: kernel/umh.c:402
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:call_modprobe
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c0820-ffffffff810c0998: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c2220)
Location: kernel/umh.c:404
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810c2220-ffffffff810c2398: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810d4d60)
Location: kernel/umh.c:404
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810d4d60-ffffffff810d4ed8: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810edd10)
Location: kernel/umh.c:404
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810edd10-ffffffff810ede98: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8110f1a0)
Location: kernel/umh.c:405
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8110f1a0-ffffffff8110f352: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8111b640)
Location: kernel/umh.c:402
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/usermode_driver.c:fork_usermode_driver
  - kernel/module/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8111b640-ffffffff8111b7f2: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff81125130)
Location: kernel/umh.c:402
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/module/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81125130-ffffffff811252e2: call_usermodehelper_exec (STB_GLOBAL)
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
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011ac48)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff80001011ac48-ffff80001011ae34: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036f1d4)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c036f1d4-c036f3b8: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c0000000001624a0)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0000000001624a0-c000000000162718: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d51a6)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0000d51a6-ffffffe0000d52e4: call_usermodehelper_exec (STB_GLOBAL)
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
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8560)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b8560-ffffffff810b86d8: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a6ea0)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810a6ea0-ffffffff810a7018: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7ac0)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810b7ac0-ffffffff810b7c38: call_usermodehelper_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info *sub_info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810bfe30)
Location: kernel/umh.c:548
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper
  - kernel/umh.c:fork_usermode_blob
  - kernel/kmod.c:__request_module
  - fs/coredump.c:do_coredump
  - security/keys/request_key.c:call_sbin_request_key
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff810bfe30-ffffffff810bffa8: call_usermodehelper_exec (STB_GLOBAL)
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
