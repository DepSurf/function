# Function: <code>notification_match</code>

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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff816eaec3)
Location: security/apparmor/notify.c:330
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_do_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool notification_match(struct aa_listener *listener, struct aa_audit_node *ad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/notify.c (0)
Location: security/apparmor/notify.c:360
Inline: False
Direct callers:
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
```
**Symbols:**

```
ffffffff817233a0-ffffffff817234fc: notification_match (STB_LOCAL)
ffffffff820f49a3-ffffffff820f49be: notification_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool notification_match(struct aa_listener *listener, struct aa_audit_node *ad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/notify.c (0)
Location: security/apparmor/notify.c:365
Inline: False
Direct callers:
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
```
**Symbols:**

```
ffffffff817646a0-ffffffff817647fc: notification_match (STB_LOCAL)
ffffffff821d1e37-ffffffff821d1e52: notification_match.cold (STB_LOCAL)
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
