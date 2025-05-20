# Function: <code>keyctl_keyring_move</code>

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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8142eef0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8142eef0-ffffffff8142efc6: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81448c20)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81448c20-ffffffff81448cf6: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149a2c0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149a2c0-ffffffff8149a396: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b7ef0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814b7ef0-ffffffff814b7fc6: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bdd70)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814bdd70-ffffffff814bde4d: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81516790)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81516790-ffffffff8151686d: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a9070)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815a9070-ffffffff815a9149: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81653290)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81653290-ffffffff81653369: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168bab0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8168bab0-ffffffff8168bb89: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c7fb0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816c7fb0-ffffffff816c8089: keyctl_keyring_move (STB_GLOBAL)
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffff800010532768)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff800010532768-ffff80001053285c: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06ea03c)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06ea03c-c06ea10c: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c00000000067ffe0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c00000000067ffe0-c000000000680138: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffe000393034)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe000393034-ffffffe0003930f6: keyctl_keyring_move (STB_GLOBAL)
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81441200)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81441200-ffffffff814412d6: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81431c70)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81431c70-ffffffff81431d46: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143d3a0)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8143d3a0-ffffffff8143d476: keyctl_keyring_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81454530)
Location: security/keys/keyctl.c:595
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81454530-ffffffff81454606: keyctl_keyring_move (STB_GLOBAL)
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
