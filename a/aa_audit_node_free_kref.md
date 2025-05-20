# Function: <code>aa_audit_node_free_kref</code>

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
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_node_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fab7a)
Location: security/apparmor/audit.c:372
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
Direct callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
```
**Symbols:**

```
ffffffff816fa600-ffffffff816fa622: aa_audit_node_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_node_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8173778a)
Location: security/apparmor/audit.c:381
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
Direct callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
```
**Symbols:**

```
ffffffff81737210-ffffffff81737232: aa_audit_node_free_kref (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
