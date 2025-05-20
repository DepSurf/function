# Function: <code>post_watch_notification</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81495fee)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff8149836c)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8149b46c)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff814b3a4e)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff814b5ddc)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff814b8efc)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff814b987e)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff814bbc5c)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff814bed4c)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff815120ae)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff815144bc)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8151776c)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff815a452c)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff815a6aeb)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff815aa1a4)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff8164e5c7)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff81650a7b)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff81654474)
Location: include/linux/watch_queue.h:103
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff81686e27)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff8168935b)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8168ccb4)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff816c3337)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff816c583b)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff816c91a4)
Location: include/linux/watch_queue.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
