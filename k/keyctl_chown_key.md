# Function: <code>keyctl_chown_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81332960)
Location: security/keys/keyctl.c:787
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81332960-ffffffff81332c5d: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813677b0)
Location: security/keys/keyctl.c:815
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813677b0-ffffffff81367aa7: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8137dfd0)
Location: security/keys/keyctl.c:815
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff8137dfd0-ffffffff8137e2c7: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81391da0)
Location: security/keys/keyctl.c:820
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81391da0-ffffffff813920ed: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b73f0)
Location: security/keys/keyctl.c:824
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813b73f0-ffffffff813b773f: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e8000)
Location: security/keys/keyctl.c:824
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff813e8000-ffffffff813e8310: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81402800)
Location: security/keys/keyctl.c:824
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81402800-ffffffff81402b10: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8142f460)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8142f460-ffffffff8142f766: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814491c0)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814491c0-ffffffff814494c6: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149a9c0)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149a9c0-ffffffff8149ad73: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b85f0)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814b85f0-ffffffff814b89a3: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814be450)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814be450-ffffffff814be7f7: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81516e70)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81516e70-ffffffff81517217: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a97b0)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815a97b0-ffffffff815a9b86: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81653a10)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81653a10-ffffffff81653de6: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168c220)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8168c220-ffffffff8168c63f: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c8720)
Location: security/keys/keyctl.c:949
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816c8720-ffffffff816c8b3f: keyctl_chown_key (STB_GLOBAL)
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
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffff800010532ce0)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff800010532ce0-ffff800010533120: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06ea5ec)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06ea5ec-c06ea9b4: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c000000000680760)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c000000000680760-c000000000680ca4: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffe00039349c)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe00039349c-ffffffe0003937ca: keyctl_chown_key (STB_GLOBAL)
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
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814417a0)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814417a0-ffffffff81441aa6: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81432210)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81432210-ffffffff81432516: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143d940)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8143d940-ffffffff8143dc46: keyctl_chown_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int keyctl_chown_key(key_serial_t id, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81454ad0)
Location: security/keys/keyctl.c:880
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81454ad0-ffffffff81454dce: keyctl_chown_key (STB_GLOBAL)
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
