# Function: <code>kvfree_sensitive</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81273050)
Location: mm/util.c:616
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
**Symbols:**

```
ffffffff81273050-ffffffff81273094: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d7b0)
Location: mm/util.c:629
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
**Symbols:**

```
ffffffff8127d7b0-ffffffff8127d7f4: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282980)
Location: mm/util.c:629
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
**Symbols:**

```
ffffffff81282980-ffffffff812829c4: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0b80)
Location: mm/util.c:635
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
**Symbols:**

```
ffffffff812c0b80-ffffffff812c0bc4: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d740)
Location: mm/util.c:668
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
**Symbols:**

```
ffffffff8131d740-ffffffff8131d7a7: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391420)
Location: mm/util.c:640
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
**Symbols:**

```
ffffffff81391420-ffffffff81391487: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3df0)
Location: mm/util.c:663
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
**Symbols:**

```
ffffffff813c3df0-ffffffff813c3e57: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kvfree_sensitive(const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee9a0)
Location: mm/util.c:676
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
**Symbols:**

```
ffffffff813ee9a0-ffffffff813eea07: kvfree_sensitive (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
