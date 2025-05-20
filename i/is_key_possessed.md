# Function: <code>is_key_possessed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:124
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/key.h:124
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/key.h:124
Inline: True
```
```
In security/keys/permission.c (0)
Location: include/linux/key.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8136547e)
Location: include/linux/key.h:124
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813665a9)
Location: include/linux/key.h:124
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (0)
Location: include/linux/key.h:124
Inline: True
```
```
In security/keys/permission.c (0)
Location: include/linux/key.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137bc9e)
Location: include/linux/key.h:124
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8137cdc9)
Location: include/linux/key.h:124
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (0)
Location: include/linux/key.h:124
Inline: True
```
```
In security/keys/permission.c (0)
Location: include/linux/key.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138f875)
Location: include/linux/key.h:125
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81390b49)
Location: include/linux/key.h:125
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (0)
Location: include/linux/key.h:125
Inline: True
```
```
In security/keys/permission.c (0)
Location: include/linux/key.h:125
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b4de4)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813b60f2)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (0)
Location: include/linux/key.h:126
Inline: True
```
```
In security/keys/permission.c (0)
Location: include/linux/key.h:126
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:126
Inline: True
```
```
In security/keys/keyring.c (ffffffff813e6766)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff813e7f92)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff813e913f)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:126
Inline: True
```
```
In security/keys/keyring.c (ffffffff81400f56)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff81402792)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff81403b6f)
Location: include/linux/key.h:126
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffff8142d786)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8142f3e2)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff814307d9)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffff814474d6)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81449142)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff8144a539)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:160
Inline: True
```
```
In security/keys/keyring.c (ffffffff81498c26)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8149a821)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff8149c079)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:160
Inline: True
```
```
In security/keys/keyring.c (ffffffff814b6696)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814b8451)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff814b9b19)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:160
Inline: True
```
```
In security/keys/keyring.c (ffffffff814bc4e6)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814be2c1)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff814bf999)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:160
Inline: True
```
```
In security/keys/keyring.c (ffffffff81514f06)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81516ce1)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff815183b9)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:160
Inline: True
```
```
In security/keys/keyring.c (ffffffff815a7676)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff815a961a)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff815aaedf)
Location: include/linux/key.h:160
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:166
Inline: True
```
```
In security/keys/keyring.c (ffffffff816516a6)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8165386a)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff8165528f)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:166
Inline: True
```
```
In security/keys/keyring.c (ffffffff81689f56)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8168c07a)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff8168dad7)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
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
In security/keys/key.c (0)
Location: include/linux/key.h:166
Inline: True
```
```
In security/keys/keyring.c (ffffffff816c6456)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff816c857a)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff816ca027)
Location: include/linux/key.h:166
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffff800010530cb0)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffff800010532c68)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffff8000105341a4)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (c06e8b24)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (c06ea580)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (c06eb8a8)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (c00000000067df10)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (c0000000006806b0)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (c00000000068218c)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffe000391e06)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffe00039344a)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffe000394400)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffff8143fab6)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81441722)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff81442b19)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffff81430526)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81432192)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff81433569)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffff8143bc56)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8143d8c2)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff8143ecb9)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/key.c (0)
Location: include/linux/key.h:143
Inline: True
```
```
In security/keys/keyring.c (ffffffff81452dc6)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81454a52)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/permission.c (ffffffff81455e69)
Location: include/linux/key.h:143
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
</details>
</li>
</ul>

## Differences
