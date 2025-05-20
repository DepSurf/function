# Function: <code>aa_lookup_perms</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160940a)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/task.c (ffffffff81610919)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
```
```
In security/apparmor/ipc.c (ffffffff8161104b)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
```
```
In security/apparmor/lsm.c (ffffffff81626b0a)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
```
```
In security/apparmor/label.c (ffffffff8162a419)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
```
```
In security/apparmor/mount.c (ffffffff816300ca)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/net.c (ffffffff816316e4)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff81632925)
Location: security/apparmor/include/policy.h:102
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:do_perms
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
In security/apparmor/apparmorfs.c (ffffffff816baee9)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/task.c (ffffffff816c3361)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
```
```
In security/apparmor/ipc.c (ffffffff816c3aa8)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
```
```
In security/apparmor/lsm.c (ffffffff816d6e16)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_prctl
```
```
In security/apparmor/label.c (ffffffff816dec29)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
```
```
In security/apparmor/mount.c (ffffffff816e4d4c)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/net.c (ffffffff816e6424)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e7735)
Location: security/apparmor/include/policy.h:104
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:do_perms
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
In security/apparmor/apparmorfs.c (ffffffff816f4925)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/task.c (ffffffff816fbeb0)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
```
```
In security/apparmor/ipc.c (ffffffff816fc69c)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
```
```
In security/apparmor/lsm.c (ffffffff8170fffa)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_prctl
```
```
In security/apparmor/label.c (ffffffff8171823e)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
```
```
In security/apparmor/mount.c (ffffffff8171e3b6)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/net.c (ffffffff8171fb35)
Location: security/apparmor/include/policy.h:131
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff817210e5)
Location: security/apparmor/include/policy.h:131
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff817316a2)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/capability.c (ffffffff81737f70)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_profile_capget
  - security/apparmor/capability.c:profile_capable
```
```
In security/apparmor/task.c (ffffffff81738e5a)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
```
```
In security/apparmor/ipc.c (ffffffff81739bf7)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
```
```
In security/apparmor/domain.c (ffffffff8173d2cb)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/lsm.c (ffffffff8174b9ac)
Location: security/apparmor/include/policy.h:137
Inline: True
```
```
In security/apparmor/label.c (ffffffff81756cae)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
```
```
In security/apparmor/mount.c (ffffffff8175cd9c)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/net.c (ffffffff8175e55a)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fc05)
Location: security/apparmor/include/policy.h:137
Inline: True
```
```
In security/apparmor/af_inet.c (ffffffff817624c1)
Location: security/apparmor/include/policy.h:137
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:match_to_prot
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/af_inet.c:do_perms
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
