# Function: <code>key_permission</code>

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
In security/keys/key.c (ffffffff8132f9bb)
Location: security/keys/internal.h:179
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81331919)
Location: security/keys/internal.h:179
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8133277f)
Location: security/keys/internal.h:179
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_read_key
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
In security/keys/key.c (ffffffff8136470b)
Location: security/keys/internal.h:180
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813666c0)
Location: security/keys/internal.h:180
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81367706)
Location: security/keys/internal.h:180
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
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
In security/keys/key.c (ffffffff8137af2b)
Location: security/keys/internal.h:180
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8137cee0)
Location: security/keys/internal.h:180
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8137df26)
Location: security/keys/internal.h:180
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
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
In security/keys/key.c (ffffffff8138eb06)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81390c29)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81391cfa)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
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
In security/keys/key.c (ffffffff813b3fb6)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813b6263)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff813b735a)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff813b9a02)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
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
In security/keys/key.c (ffffffff813e46a3)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813e69fe)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff813e7f51)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff813ea7b0)
Location: security/keys/internal.h:186
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
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
In security/keys/key.c (ffffffff813fee93)
Location: security/keys/internal.h:184
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814011fe)
Location: security/keys/internal.h:184
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81402751)
Location: security/keys/internal.h:184
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff814051cc)
Location: security/keys/internal.h:184
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
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
In security/keys/key.c (ffffffff8142b063)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8142da1a)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8142f3a1)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff81432211)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffff81444db3)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8144776a)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81449101)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff8144bf71)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffff81496743)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81498f3d)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8149a7dc)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff8149de6d)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff814b41b3)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814b69bd)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff814b840c)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff814bb94d)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff814b9fe3)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814bc805)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff814be27c)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff814c1815)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff81512813)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81515225)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81516c9c)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff8151a285)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff815a4d1a)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff815a79c2)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff815a95cb)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff815ad00d)
Location: security/keys/internal.h:207
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff8164e37a)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81651a22)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8165381b)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff8165753d)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff81686bda)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8168a2ce)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8168c02b)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff8168fdd4)
Location: security/keys/internal.h:205
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffffffff816c30ea)
Location: security/keys/internal.h:199
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff816c67ce)
Location: security/keys/internal.h:199
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff816c852b)
Location: security/keys/internal.h:199
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff816cc364)
Location: security/keys/internal.h:199
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
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
In security/keys/key.c (ffff80001052dba0)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffff800010530fec)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffff800010532c28)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffff800010535cac)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (c06e6288)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c06e8de0)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (c06ea544)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (c06ecec8)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (c000000000679f80)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c00000000067e4e0)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (c000000000680650)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (c000000000683fb0)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffe00038f6fc)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffe000392086)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffe000393414)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffe000395638)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffff8143d393)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8143fd4a)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff814416e1)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff81444551)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffff8142de03)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814307ba)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81432151)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff81434fa1)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffff81439533)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8143beea)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff8143d881)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff81440611)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
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
In security/keys/key.c (ffffffff81450723)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8145306a)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (ffffffff81454a11)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
```
In security/keys/request_key.c (ffffffff81457894)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
</ul>

## Differences
