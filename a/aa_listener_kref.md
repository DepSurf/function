# Function: <code>aa_listener_kref</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aa_listener_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff816eb5ee)
Location: security/apparmor/notify.c:164
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
Direct callers:
  - security/apparmor/apparmorfs.c:listener_release
```
**Symbols:**

```
ffffffff816ea670-ffffffff816ea686: aa_listener_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_listener_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff8172404e)
Location: security/apparmor/notify.c:224
Inline: True
Inline callers:
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
Direct callers:
  - security/apparmor/apparmorfs.c:listener_release
```
**Symbols:**

```
ffffffff81724510-ffffffff81724526: aa_listener_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_listener_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff8176534e)
Location: security/apparmor/notify.c:226
Inline: True
Inline callers:
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
Direct callers:
  - security/apparmor/apparmorfs.c:listener_release
```
**Symbols:**

```
ffffffff81765840-ffffffff81765856: aa_listener_kref (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
