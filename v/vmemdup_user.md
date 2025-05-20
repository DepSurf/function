# Function: <code>vmemdup_user</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214700)
Location: mm/util.c:182
Inline: False
```
**Symbols:**

```
ffffffff81214700-ffffffff81214778: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812275e0)
Location: mm/util.c:175
Inline: False
```
**Symbols:**

```
ffffffff812275e0-ffffffff81227658: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237370)
Location: mm/util.c:187
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff81237370-ffffffff812373f6: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812452b0)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff812452b0-ffffffff81245341: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812730a0)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff812730a0-ffffffff81273142: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d800)
Location: mm/util.c:195
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff8127d800-ffffffff8127d8a2: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812829d0)
Location: mm/util.c:195
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff812829d0-ffffffff81282a72: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0c50)
Location: mm/util.c:195
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff812c0c50-ffffffff812c0cf2: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d920)
Location: mm/util.c:196
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - fs/xattr.c:setxattr_copy
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff8131d920-ffffffff8131d9cc: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391540)
Location: mm/util.c:196
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - fs/xattr.c:setxattr_copy
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff81391540-ffffffff813915ec: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3e70)
Location: mm/util.c:219
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - fs/xattr.c:setxattr_copy
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff813c3e70-ffffffff813c3f1c: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813eea20)
Location: mm/util.c:219
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - fs/xattr.c:setxattr_copy
  - fs/pstore/platform.c:pstore_write_user_compat
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff813eea20-ffffffff813eeacc: vmemdup_user (STB_GLOBAL)
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
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d86e0)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffff8000102d86e0-ffff8000102d8798: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff840)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_user_tlv
```
**Symbols:**

```
c04ff840-c04ff954: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003984a0)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
c0000000003984a0-c0000000003985b0: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2e20)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffe0001f2e20-ffffffe0001f2ebc: vmemdup_user (STB_GLOBAL)
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
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d900)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff8123d900-ffffffff8123d991: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230900)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff81230900-ffffffff81230991: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b6a0)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff8123b6a0-ffffffff8123b731: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vmemdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124adb0)
Location: mm/util.c:194
Inline: False
Direct callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
**Symbols:**

```
ffffffff8124adb0-ffffffff8124ae41: vmemdup_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
