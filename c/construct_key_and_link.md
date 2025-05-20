# Function: <code>construct_key_and_link</code>

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
In security/keys/request_key.c (ffffffff81334bcb)
Location: security/keys/request_key.c:430
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
In security/keys/request_key.c (ffffffff81369b7e)
Location: security/keys/request_key.c:430
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
In security/keys/request_key.c (ffffffff8138038e)
Location: security/keys/request_key.c:430
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
In security/keys/request_key.c (ffffffff81394208)
Location: security/keys/request_key.c:431
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
In security/keys/request_key.c (ffffffff813b97bd)
Location: security/keys/request_key.c:454
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
In security/keys/request_key.c (ffffffff813ea52d)
Location: security/keys/request_key.c:454
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
In security/keys/request_key.c (ffffffff81404f9f)
Location: security/keys/request_key.c:440
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/request_key.c (0)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81431ee0-ffffffff814323c3: construct_key_and_link (STB_LOCAL)
ffffffff81432684-ffffffff81432697: construct_key_and_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8144bc40)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8144bc40-ffffffff8144c121: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8149e030)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8149e030-ffffffff8149e1d1: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814bbb10)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814bbb10-ffffffff814bbcb1: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814c19d0)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814c19d0-ffffffff814c1b8c: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8151a5f4)
Location: security/keys/request_key.c:473
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815ad38b)
Location: security/keys/request_key.c:473
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81657700)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81657700-ffffffff816578b0: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8168ff80)
Location: security/keys/request_key.c:489
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8168ff80-ffffffff81690126: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816cc510)
Location: security/keys/request_key.c:489
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff816cc510-ffffffff816cc6b6: construct_key_and_link (STB_LOCAL)
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
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffff8000105359a8)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffff8000105359a8-ffff800010535e34: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c06ecc08)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
c06ecc08-c06ed0d8: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c000000000683bf0)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
c000000000683bf0-c000000000684298: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffe000395416)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffe000395416-ffffffe0003957f2: construct_key_and_link (STB_LOCAL)
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
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81444220)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81444220-ffffffff81444701: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81434c70)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81434c70-ffffffff81435151: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814402e0)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814402e0-ffffffff814407c1: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *construct_key_and_link(struct keyring_search_context *ctx, const char *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81457560)
Location: security/keys/request_key.c:473
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81457560-ffffffff81457a83: construct_key_and_link (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
