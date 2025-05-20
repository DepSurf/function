# Function: <code>find_keyring_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool skip_perm_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81331820)
Location: security/keys/keyring.c:976
Inline: False
Direct callers:
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff81331820-ffffffff81331976: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool skip_perm_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813665c0)
Location: security/keys/keyring.c:1000
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
```
**Symbols:**

```
ffffffff813665c0-ffffffff81366715: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool skip_perm_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137cde0)
Location: security/keys/keyring.c:1000
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
```
**Symbols:**

```
ffffffff8137cde0-ffffffff8137cf35: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool skip_perm_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81390b60)
Location: security/keys/keyring.c:1112
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
```
**Symbols:**

```
ffffffff81390b60-ffffffff81390ca2: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b6100)
Location: security/keys/keyring.c:1109
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
```
**Symbols:**

```
ffffffff813b6100-ffffffff813b6293: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e6910)
Location: security/keys/keyring.c:1102
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
```
**Symbols:**

```
ffffffff813e6910-ffffffff813e6a9a: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81401110)
Location: security/keys/keyring.c:1100
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
```
**Symbols:**

```
ffffffff81401110-ffffffff8140129a: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142d950)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff8142d950-ffffffff8142da86: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814476a0)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff814476a0-ffffffff814477d6: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81498e40)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff81498e40-ffffffff81498f88: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b68c0)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff814b68c0-ffffffff814b6a08: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bc710)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff814bc710-ffffffff814bc850: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81515130)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff81515130-ffffffff81515270: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a78c0)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff815a78c0-ffffffff815a7a16: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81651920)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff81651920-ffffffff81651a76: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8168a1d0)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff8168a1d0-ffffffff8168a322: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c66d0)
Location: security/keys/keyring.c:1141
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff816c66d0-ffffffff816c6822: find_keyring_by_name (STB_GLOBAL)
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
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff800010530ec8)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffff800010530ec8-ffff800010531038: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e8d08)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
c06e8d08-c06e8e58: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067e1e0)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
c00000000067e1e0-c00000000067e558: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe000391fd2)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffe000391fd2-ffffffe0003920d8: find_keyring_by_name (STB_GLOBAL)
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
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143fc80)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff8143fc80-ffffffff8143fdb6: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814306f0)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff814306f0-ffffffff81430826: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143be20)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff8143be20-ffffffff8143bf56: find_keyring_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *find_keyring_by_name(const char *name, bool uid_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81452fa0)
Location: security/keys/keyring.c:1143
Inline: False
Direct callers:
  - security/keys/process_keys.c:join_session_keyring
```
**Symbols:**

```
ffffffff81452fa0-ffffffff814530d5: find_keyring_by_name (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool uid_keyring</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_perm_check</code>
</li>
</ul>
</details>
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
