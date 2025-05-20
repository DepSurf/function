# Function: <code>check_cached_key</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81431a30)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81431a30-ffffffff81431a8b: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8144b790)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8144b790-ffffffff8144b7eb: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8149d8bd)
Location: security/keys/request_key.c:22
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
Direct callers:
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8149d7b0-ffffffff8149d82f: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814bb2d0)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814bb2d0-ffffffff814bb34f: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814c1190)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814c1190-ffffffff814c120f: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81519c00)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81519c00-ffffffff81519c7f: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815ac890)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff815ac890-ffffffff815ac913: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81656d90)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81656d90-ffffffff81656e13: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8168f580)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8168f580-ffffffff8168f603: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816cbb10)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff816cbb10-ffffffff816cbb93: check_cached_key (STB_LOCAL)
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
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffff800010535418)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffff800010535418-ffff800010535490: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c06eca4c)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
c06eca4c-c06ecabc: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c0000000006838d0)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
c0000000006838d0-c00000000068397c: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffe000395234)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffe000395234-ffffffe00039528c: check_cached_key (STB_LOCAL)
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
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81443d70)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81443d70-ffffffff81443dcb: check_cached_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814347c0)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814347c0-ffffffff8143481b: check_cached_key (STB_LOCAL)
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
In security/keys/request_key.c (0)
Location: security/keys/request_key.c:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *check_cached_key(struct keyring_search_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814570b0)
Location: security/keys/request_key.c:22
Inline: False
Direct callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814570b0-ffffffff8145710b: check_cached_key (STB_LOCAL)
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
