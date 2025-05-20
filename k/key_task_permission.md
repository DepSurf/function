# Function: <code>key_task_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81333730)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81333730-ffffffff813337ca: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff813685c0)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff813685c0-ffffffff8136865b: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8137edd0)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff8137edd0-ffffffff8137ee6b: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81392d30)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81392d30-ffffffff81392dd0: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff813b8390)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff813b8390-ffffffff813b8430: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff813e9100)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff813e9100-ffffffff813e91a0: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81403b30)
Location: security/keys/permission.c:30
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81403b30-ffffffff81403bd0: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff814307a0)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff814307a0-ffffffff81430839: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8144a500)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff8144a500-ffffffff8144a599: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8149c010)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff8149c010-ffffffff8149c14b: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff814b9ab0)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff814b9ab0-ffffffff814b9beb: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff814bf930)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff814bf930-ffffffff814bfa6b: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81518350)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff81518350-ffffffff8151848b: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff815aae60)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff815aae60-ffffffff815aaf83: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81655210)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff81655210-ffffffff81655333: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8168da40)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff8168da40-ffffffff8168db64: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff816c9f90)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:key_get_persistent
```
**Symbols:**

```
ffffffff816c9f90-ffffffff816ca0b4: key_task_permission (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffff800010534150)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffff800010534150-ffff800010534218: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (c06eb854)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
c06eb854-c06eb910: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (c000000000682130)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
c000000000682130-c000000000682238: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffe0003943b8)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffe0003943b8-ffffffe000394460: key_task_permission (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81442ae0)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81442ae0-ffffffff81442b79: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81433530)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81433530-ffffffff814335c9: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8143ec80)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff8143ec80-ffffffff8143ed19: key_task_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred *cred, unsigned int perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81455e30)
Location: security/keys/permission.c:26
Inline: False
Direct callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81455e30-ffffffff81455ec9: key_task_permission (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum key_need_perm need_perm</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int perm</code>
</li>
</ul>
</details>
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
