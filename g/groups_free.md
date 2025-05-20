# Function: <code>groups_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a4290)
Location: kernel/groups.c:51
Inline: False
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/groups.c:set_groups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/uid16.c:SyS_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810a4290-ffffffff810a42e6: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a79d0)
Location: kernel/groups.c:51
Inline: False
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/uid16.c:SyS_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810a79d0-ffffffff810a7a26: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810adf0e)
Location: kernel/groups.c:32
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:SyS_setgroups16
  - kernel/uid16.c:SyS_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810adb90-ffffffff810adba0: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aaa24)
Location: kernel/groups.c:33
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:SyS_setgroups16
  - kernel/uid16.c:SyS_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810aa770-ffffffff810aa780: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b1708)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:SyS_setgroups16
  - kernel/uid16.c:SyS_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810b1430-ffffffff810b1440: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8651)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810b8240-ffffffff810b8250: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c16e5)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810c1320-ffffffff810c1330: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c77dc)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810c7410-ffffffff810c7420: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d08ac)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810d04e0-ffffffff810d04f0: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da746)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810da320-ffffffff810da330: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5ea6)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810d5a80-ffffffff810d5a90: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7b94)
Location: kernel/groups.c:29
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810d7740-ffffffff810d7750: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb444)
Location: kernel/groups.c:29
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810eaff0-ffffffff810eb000: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8110636b)
Location: kernel/groups.c:29
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff81105e80-ffffffff81105e96: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bfbf)
Location: kernel/groups.c:29
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff8112ba10-ffffffff8112ba26: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138e1f)
Location: kernel/groups.c:29
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff81138870-ffffffff81138886: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143be8)
Location: kernel/groups.c:29
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__do_sys_setgroups16
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff81143540-ffffffff81143556: groups_free (STB_GLOBAL)
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
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010131378)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffff800010130c70-ffff800010130c9c: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c03807c0)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__se_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
c038040c-c0380428: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017aa08)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
c00000000017a300-c00000000017a334: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e430e)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_current_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffe0000e3f96-ffffffe0000e3fc0: groups_free (STB_GLOBAL)
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
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810cac2c)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810ca860-ffffffff810ca870: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b943c)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810b9070-ffffffff810b9080: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca15c)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810c9d90-ffffffff810c9da0: groups_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void groups_free(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d26ac)
Location: kernel/groups.c:34
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - net/ipv4/ping.c:ping_init_sock
```
**Symbols:**

```
ffffffff810d22e0-ffffffff810d22f0: groups_free (STB_GLOBAL)
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
