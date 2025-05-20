# Function: <code>__post_watch_notification</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124cba0)
Location: kernel/watch_queue.c:175
Inline: True
Direct callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff8124cba0-ffffffff8124cc9f: __post_watch_notification.part.0 (STB_LOCAL)
ffffffff8124cca0-ffffffff8124ccb9: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (ffffffff81256fe0)
Location: kernel/watch_queue.c:175
Inline: True
Direct callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81256fe0-ffffffff812570e4: __post_watch_notification.part.0 (STB_LOCAL)
ffffffff812570f0-ffffffff81257109: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b6f0)
Location: kernel/watch_queue.c:175
Inline: True
Direct callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff8125b6f0-ffffffff8125b801: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81297500)
Location: kernel/watch_queue.c:176
Inline: True
Direct callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81297500-ffffffff8129767e: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (ffffffff812ed350)
Location: kernel/watch_queue.c:198
Inline: True
Direct callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff812ed190-ffffffff812ed343: __post_watch_notification.part.0 (STB_LOCAL)
ffffffff81e6b288-ffffffff81e6b2a3: __post_watch_notification.part.0.cold (STB_LOCAL)
ffffffff812ed350-ffffffff812ed381: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (ffffffff813576f0)
Location: kernel/watch_queue.c:198
Inline: True
Direct callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81357520-ffffffff813576d3: __post_watch_notification.part.0 (STB_LOCAL)
ffffffff82061ff9-ffffffff82062014: __post_watch_notification.part.0.cold (STB_LOCAL)
ffffffff813576f0-ffffffff81357721: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (ffffffff81388da0)
Location: kernel/watch_queue.c:194
Inline: True
Direct callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81388da0-ffffffff81388f49: __post_watch_notification.part.0 (STB_LOCAL)
ffffffff81388f60-ffffffff81388f91: __post_watch_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __post_watch_notification(struct watch_list *wlist, struct watch_notification *n, const struct cred *cred, u64 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b27f0)
Location: kernel/watch_queue.c:194
Inline: True
Direct callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff813b27f0-ffffffff813b2999: __post_watch_notification.part.0 (STB_LOCAL)
ffffffff813b29b0-ffffffff813b29e1: __post_watch_notification (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
