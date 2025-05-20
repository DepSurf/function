# Function: <code>get_group_info</code>

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
In kernel/cred.c (ffffffff810a20e6)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810a4438)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff81334516)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff817a2868)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810a5896)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810a7b41)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff813694a6)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff818100da)
Location: include/linux/cred.h:49
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810ab4f6)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810adc71)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8137fcb6)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff8184161f)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810a80b6)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810aa7c6)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff81393b36)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81862e5d)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810ae786)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810b1471)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff813b91c6)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff818e2f95)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810b5ab1)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810b826e)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff813e9f56)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff8193990e)
Location: include/linux/cred.h:45
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810becb7)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810c134e)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8140499c)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff8196959e)
Location: include/linux/cred.h:44
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810c4d28)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810c743e)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8143184d)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff819d01e4)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810cde38)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810d050e)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8144b5ad)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81a06d34)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810d7bcf)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810da34e)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8149d2d1)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81af67b6)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810d2a23)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810d5aae)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff814bada6)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81b0363d)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810d463b)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810d776e)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff814c0c74)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81aeee7d)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810e781b)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810eb01e)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff815196b6)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81baf24d)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff81101aa4)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff81105ebe)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff815ac286)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81d4258b)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff81126c74)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff8112ba5e)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff81656716)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/safesetid/lsm.c (ffffffff816ecab5)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In net/ipv4/ping.c (ffffffff81f0b41b)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff81134114)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff811388be)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8168ef56)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/safesetid/lsm.c (ffffffff81726ee5)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In net/ipv4/ping.c (ffffffff81f6affb)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff8113f0b5)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff8114379b)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff816cb4ad)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/safesetid/lsm.c (ffffffff81768135)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In net/ipv4/ping.c (ffffffff82032a42)
Location: include/linux/cred.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffff80001012d090)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffff80001013114c)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffff8000105351f4)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffff800010cc0dc8)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (c037d564)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (c0380470)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (c06ec8ec)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (c0dcbd10)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (c000000000176380)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (c00000000017a38c)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (c0000000006837c8)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (c000000000ddae48)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffe0000e1808)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffe0000e407e)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_current_groups
```
```
In security/keys/process_keys.c (ffffffe0003951a6)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffe00081600c)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810c81b8)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810ca88e)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff81443b8d)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff819a6ad4)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810b69d8)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810b909e)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff814345dd)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81960594)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810c7708)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810c9dbe)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff8143fd2d)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81a11374)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
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
In kernel/cred.c (ffffffff810cfbd8)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/groups.c (ffffffff810d230e)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In security/keys/process_keys.c (ffffffff81456edd)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/ipv4/ping.c (ffffffff81a1bce4)
Location: include/linux/cred.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
</details>
</li>
</ul>

## Differences
