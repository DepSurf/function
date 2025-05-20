# Function: <code>cap_intersect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81096460)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kmod.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8133aa99)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff81384332)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81099820)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kmod.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8137020c)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff813be171)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109e7d0)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kmod.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff81386a1c)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff813d55f1)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109be34)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kmod.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8139b6ec)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff813e7f9d)
Location: include/linux/capability.h:124
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a2b24)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff813c0cfc)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8140f2d8)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a9886)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff813f1c6c)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff814412d9)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b2526)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8140cf3c)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8145e264)
Location: include/linux/capability.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b80b7)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8143a0e9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8148b845)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810be5b7)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff81453f59)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff814a5705)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c5a64)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff814a6a0b)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff81500cb7)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c0d60)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff814c3fbb)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8151dffc)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c2760)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff814ca2f9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff815247f8)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810d52a0)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff81523101)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff81582a88)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810edaa0)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff815b59f9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff81621f89)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8110ef10)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff81660ae9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff816d58a9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8111b3c3)
Location: include/linux/capability.h:83
Inline: True
Inline callers:
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff81699677)
Location: include/linux/capability.h:83
Inline: True
Inline callers:
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8170ea52)
Location: include/linux/capability.h:83
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff81124ea3)
Location: include/linux/capability.h:83
Inline: True
Inline callers:
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff816d5d27)
Location: include/linux/capability.h:83
Inline: True
Inline callers:
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8174cac0)
Location: include/linux/capability.h:83
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011b1c8)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffff80001053f09c)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffff80001059ba48)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036f5f8)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (c06f5074)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (c074c95c)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c000000000162890)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (c00000000068fa10)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (c000000000714850)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d5816)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffe00039c652)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_raise_fs_set
```
```
In security/apparmor/lsm.c (ffffffe0003e8ac2)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8927)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8144c539)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8149dce5)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a7261)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8143cf89)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff8148e705)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7e87)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff814485d9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff81499d85)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c006e)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In security/commoncap.c (ffffffff8145f9a9)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
```
```
In security/apparmor/lsm.c (ffffffff814b2a51)
Location: include/linux/capability.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
```
</details>
</li>
</ul>

## Differences
