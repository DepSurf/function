# Function: <code>__listener_complete_held_user_pending</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
void __listener_complete_held_user_pending(struct aa_listener *listener, struct aa_knotif *knotif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff81723fc0)
Location: security/apparmor/notify.c:536
Inline: False
Direct callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:aa_listener_unotif_response
```
**Symbols:**

```
ffffffff81723fc0-ffffffff8172408b: __listener_complete_held_user_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __listener_complete_held_user_pending(struct aa_listener *listener, struct aa_knotif *knotif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff817652c0)
Location: security/apparmor/notify.c:541
Inline: False
Direct callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:aa_listener_unotif_response
```
**Symbols:**

```
ffffffff817652c0-ffffffff8176538b: __listener_complete_held_user_pending (STB_LOCAL)
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
