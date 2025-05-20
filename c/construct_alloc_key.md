# Function: <code>construct_alloc_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81334c28)
Location: security/keys/request_key.c:330
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81369bdb)
Location: security/keys/request_key.c:330
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813803eb)
Location: security/keys/request_key.c:330
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81394262)
Location: security/keys/request_key.c:331
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813b9813)
Location: security/keys/request_key.c:354
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813ea58a)
Location: security/keys/request_key.c:354
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81404ffc)
Location: security/keys/request_key.c:340
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81431f72)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8144bcd2)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8149d480)
Location: security/keys/request_key.c:366
Inline: False
Direct callers:
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8149d480-ffffffff8149d6b7: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814baf80)
Location: security/keys/request_key.c:366
Inline: False
Direct callers:
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff814baf80-ffffffff814bb1d9: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814c0e30)
Location: security/keys/request_key.c:366
Inline: False
Direct callers:
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff814c0e30-ffffffff814c1089: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815198a0)
Location: security/keys/request_key.c:366
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff815198a0-ffffffff81519af9: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815ac4a0)
Location: security/keys/request_key.c:366
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff815ac4a0-ffffffff815ac751: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81656960)
Location: security/keys/request_key.c:366
Inline: False
Direct callers:
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff81656960-ffffffff81656c11: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8168f1a0)
Location: security/keys/request_key.c:369
Inline: False
Direct callers:
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8168f1a0-ffffffff8168f491: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int construct_alloc_key(struct keyring_search_context *ctx, struct key *dest_keyring, long unsigned int flags, struct key_user *user, struct key **_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816cb730)
Location: security/keys/request_key.c:369
Inline: False
Direct callers:
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff816cb730-ffffffff816cba21: construct_alloc_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffff800010535a3c)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c06eccac)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c000000000683cb8)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffe000395484)
Location: security/keys/request_key.c:366
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814442b2)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81434d02)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81440372)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814575fa)
Location: security/keys/request_key.c:366
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
</details>
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
