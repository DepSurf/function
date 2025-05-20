# Function: <code>iterate_supers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81210000)
Location: fs/super.c:555
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/buffer.c:do_thaw_all
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:SyS_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81210000-ffffffff8121010c: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81236ac0)
Location: fs/super.c:569
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/buffer.c:do_thaw_all
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:SyS_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81236ac0-ffffffff81236bc7: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81249770)
Location: fs/super.c:582
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/buffer.c:do_thaw_all
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:SyS_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81249770-ffffffff81249877: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812550a0)
Location: fs/super.c:585
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/buffer.c:do_thaw_all
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:SyS_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812550a0-ffffffff812551a7: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81277230)
Location: fs/super.c:585
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
  - fs/buffer.c:do_thaw_all
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:SyS_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81277230-ffffffff8127733a: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129dc10)
Location: fs/super.c:617
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff8129dc10-ffffffff8129dd04: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b2bd0)
Location: fs/super.c:621
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812b2bd0-ffffffff812b2cc4: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf860)
Location: fs/super.c:675
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812cf860-ffffffff812cf967: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e1310)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812e1310-ffffffff812e1401: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318670)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81318670-ffffffff81318777: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323a90)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81323a90-ffffffff81323b97: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329b50)
Location: fs/super.c:682
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81329b50-ffffffff81329c57: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377180)
Location: fs/super.c:682
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff81377180-ffffffff81377287: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6410)
Location: fs/super.c:681
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff813f6410-ffffffff813f6501: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147f4f0)
Location: fs/super.c:724
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff8147f4f0-ffffffff8147f5e1: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4140)
Location: fs/super.c:731
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff814b4140-ffffffff814b4231: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6890)
Location: fs/super.c:908
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff814e6890-ffffffff814e6969: iterate_supers (STB_GLOBAL)
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
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103884b8)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffff8000103884b8-ffff80001038869c: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0570ca4)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
c0570ca4-c0570dc0: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047f1f0)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
c00000000047f1f0-c00000000047f3f0: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025ab34)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffe00025ab34-ffffffe00025accc: iterate_supers (STB_GLOBAL)
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
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d98f0)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812d98f0-ffffffff812d99e1: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ca570)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812ca570-ffffffff812ca661: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7700)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812d7700-ffffffff812d77f1: iterate_supers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iterate_supers(void (*f)(struct super_block *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8550)
Location: fs/super.c:681
Inline: False
Direct callers:
  - mm/cleancache.c:cleancache_register_ops
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/quota/quota.c:kernel_quotactl
  - security/selinux/hooks.c:selinux_complete_init
  - security/selinux/hooks.c:selinux_complete_init
```
**Symbols:**

```
ffffffff812e8550-ffffffff812e8631: iterate_supers (STB_GLOBAL)
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
