# Function: <code>aa_put_audit_node</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fab69)
Location: security/apparmor/include/audit.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/file.c (ffffffff8171531b)
Location: security/apparmor/include/audit.h:270
Inline: True
```
```
In security/apparmor/notify.c (ffffffff8172544d)
Location: security/apparmor/include/audit.h:270
Inline: True
Inline callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
  - security/apparmor/notify.c:__listener_del_knotif
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
In security/apparmor/audit.c (ffffffff81737779)
Location: security/apparmor/include/audit.h:278
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/file.c (ffffffff81753d9b)
Location: security/apparmor/include/audit.h:278
Inline: True
```
```
In security/apparmor/notify.c (ffffffff817665dd)
Location: security/apparmor/include/audit.h:278
Inline: True
Inline callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
  - security/apparmor/notify.c:__listener_del_knotif
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
