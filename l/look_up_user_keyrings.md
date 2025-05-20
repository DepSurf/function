# Function: <code>look_up_user_keyrings</code>

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
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81430950)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff81430950-ffffffff81430c4f: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8144a6b0)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff8144a6b0-ffffffff8144a9af: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8149c1c0)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff8149c1c0-ffffffff8149c4b1: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814b9c60)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff814b9c60-ffffffff814b9f51: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814bfae0)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff814bfae0-ffffffff814bfdd1: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81518500)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff81518500-ffffffff815187f1: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff815ab000)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff815ab000-ffffffff815ab30c: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff816553e0)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff816553e0-ffffffff816556ec: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8168dc10)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff8168dc10-ffffffff8168df1c: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff816ca160)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff816ca160-ffffffff816ca46c: look_up_user_keyrings (STB_GLOBAL)
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
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffff800010534378)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffff800010534378-ffff800010534624: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (c06eba6c)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
c06eba6c-c06ebd3c: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (c000000000682450)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
c000000000682450-c0000000006827f0: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffe00039458e)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffe00039458e-ffffffe0003947d0: look_up_user_keyrings (STB_GLOBAL)
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
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81442c90)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff81442c90-ffffffff81442f8f: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814336e0)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff814336e0-ffffffff814339df: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143ee30)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff8143ee30-ffffffff8143f12f: look_up_user_keyrings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key **_user_keyring, struct key **_user_session_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81455fe0)
Location: security/keys/process_keys.c:74
Inline: False
Direct callers:
  - security/keys/process_keys.c:init_root_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
**Symbols:**

```
ffffffff81455fe0-ffffffff814562df: look_up_user_keyrings (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
