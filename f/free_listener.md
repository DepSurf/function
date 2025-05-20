# Function: <code>free_listener</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_listener(struct aa_listener *listener);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff816e9b90)
Location: security/apparmor/notify.c:108
Inline: False
Direct callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
```
**Symbols:**

```
ffffffff816e9b90-ffffffff816e9e68: free_listener (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_listener(struct aa_listener *listener);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff81723c40)
Location: security/apparmor/notify.c:166
Inline: False
Direct callers:
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
```
**Symbols:**

```
ffffffff81723c40-ffffffff81723fa2: free_listener (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_listener(struct aa_listener *listener);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff81764f40)
Location: security/apparmor/notify.c:168
Inline: False
Direct callers:
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
```
**Symbols:**

```
ffffffff81764f40-ffffffff817652a2: free_listener (STB_LOCAL)
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
