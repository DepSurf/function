# Function: <code>strndup_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abdd0)
Location: mm/util.c:155
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:perf_ioctl
  - fs/namespace.c:SyS_mount
  - fs/namespace.c:SyS_mount
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
```
**Symbols:**

```
ffffffff811abdd0-ffffffff811abe2a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4ab0)
Location: mm/util.c:155
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:perf_ioctl
  - fs/namespace.c:SyS_mount
  - fs/namespace.c:SyS_mount
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
```
**Symbols:**

```
ffffffff811c4ab0-ffffffff811c4b0a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4bc0)
Location: mm/util.c:155
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:perf_ioctl
  - fs/namespace.c:SyS_mount
  - fs/namespace.c:SyS_mount
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
```
**Symbols:**

```
ffffffff811d4bc0-ffffffff811d4c1a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd9f0)
Location: mm/util.c:182
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:perf_ioctl
  - fs/namespace.c:SyS_mount
  - fs/namespace.c:SyS_mount
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff811dd9f0-ffffffff811dda4a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3470)
Location: mm/util.c:182
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:perf_ioctl
  - fs/namespace.c:SyS_mount
  - fs/namespace.c:SyS_mount
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff811f3470-ffffffff811f34ca: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812146a0)
Location: mm/util.c:204
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff812146a0-ffffffff812146fa: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227580)
Location: mm/util.c:197
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff81227580-ffffffff812275da: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237310)
Location: mm/util.c:211
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81237310-ffffffff8123736a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245580)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81245580-ffffffff812455da: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812731e0)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff812731e0-ffffffff8127323a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d940)
Location: mm/util.c:219
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8127d940-ffffffff8127d99a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282b10)
Location: mm/util.c:219
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81282b10-ffffffff81282b6a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0b20)
Location: mm/util.c:219
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff812c0b20-ffffffff812c0b7a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d050)
Location: mm/util.c:220
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/module/main.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8131d050-ffffffff8131d0ba: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81390970)
Location: mm/util.c:220
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/module/main.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81390970-ffffffff813909da: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3270)
Location: mm/util.c:243
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/module/main.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff813c3270-ffffffff813c32da: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813edd90)
Location: mm/util.c:243
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/module/main.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/events/core.c:_perf_ioctl
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff813edd90-ffffffff813eddfa: strndup_user (STB_GLOBAL)
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
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8858)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffff8000102d8858-ffff8000102d88d8: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ffa68)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
c04ffa68-c04ffac8: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003983d0)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
c0000000003983d0-c0000000003984a0: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2db8)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
ffffffe0001f2db8-ffffffe0001f2e20: strndup_user (STB_GLOBAL)
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
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123dbd0)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff8123dbd0-ffffffff8123dc2a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230bd0)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81230bd0-ffffffff81230c2a: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b970)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8123b970-ffffffff8123b9ca: strndup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strndup_user(const char *s, long int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124b080)
Location: mm/util.c:218
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:ksys_mount
  - fs/namespace.c:ksys_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_join_session_keyring
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8124b080-ffffffff8124b0da: strndup_user (STB_GLOBAL)
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
