# Function: <code>wait_for_key_construction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81334a00)
Location: security/keys/request_key.c:589
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_with_auxdata
```
**Symbols:**

```
ffffffff81334a00-ffffffff81334a77: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813699b0)
Location: security/keys/request_key.c:589
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813699b0-ffffffff81369a25: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813801c0)
Location: security/keys/request_key.c:589
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813801c0-ffffffff81380235: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81394040)
Location: security/keys/request_key.c:590
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff81394040-ffffffff813940b5: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813b9310)
Location: security/keys/request_key.c:616
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813b9310-ffffffff813b937a: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813ea080)
Location: security/keys/request_key.c:616
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813ea080-ffffffff813ea0e8: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81404ab0)
Location: security/keys/request_key.c:603
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff81404ab0-ffffffff81404b18: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81431970)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81431970-ffffffff814319de: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8144b6d0)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8144b6d0-ffffffff8144b73e: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8149d6c0)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8149d6c0-ffffffff8149d732: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814bb1e0)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff814bb1e0-ffffffff814bb252: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814c10b0)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff814c10b0-ffffffff814c111a: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81519b20)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81519b20-ffffffff81519b8a: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815ac790)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff815ac790-ffffffff815ac804: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81656c70)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81656c70-ffffffff81656ce9: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8168f4f0)
Location: security/keys/request_key.c:676
Inline: False
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8168f4f0-ffffffff8168f569: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816cba80)
Location: security/keys/request_key.c:676
Inline: False
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff816cba80-ffffffff816cbaf9: wait_for_key_construction (STB_GLOBAL)
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
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffff8000105354c8)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffff8000105354c8-ffff800010535548: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c06ed43c)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
c06ed43c-c06ed4c0: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c0000000006846e0)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
c0000000006846e0-c00000000068479c: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffe000395ae2)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffe000395ae2-ffffffe000395b68: wait_for_key_construction (STB_GLOBAL)
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
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81443cb0)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81443cb0-ffffffff81443d1e: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81434700)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81434700-ffffffff8143476e: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8143ff20)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8143ff20-ffffffff8143ff8e: wait_for_key_construction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wait_for_key_construction(struct key *key, bool intr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81457000)
Location: security/keys/request_key.c:660
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81457000-ffffffff8145705d: wait_for_key_construction (STB_GLOBAL)
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
