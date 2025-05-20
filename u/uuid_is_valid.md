# Function: <code>uuid_is_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81441d50)
Location: lib/uuid.c:83
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:__uuid_to_bin
```
**Symbols:**

```
ffffffff81441d50-ffffffff81441d91: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8145ef60)
Location: lib/uuid.c:83
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:__uuid_to_bin
```
**Symbols:**

```
ffffffff8145ef60-ffffffff8145efa1: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814642b0)
Location: lib/uuid.c:86
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff814642b0-ffffffff814642f0: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81490230)
Location: lib/uuid.c:86
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81490230-ffffffff81490270: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814c5020)
Location: lib/uuid.c:86
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff814c5020-ffffffff814c505a: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814d9710)
Location: lib/uuid.c:86
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff814d9710-ffffffff814d9757: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81505470)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81505470-ffffffff815054b7: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81523450)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81523450-ffffffff81523497: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815869a0)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff815869a0-ffffffff815869e7: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815a3c90)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff815a3c90-ffffffff815a3cd7: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815aabb0)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff815aabb0-ffffffff815aabe9: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81613e60)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff81613e60-ffffffff81613e99: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff816e06f0)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff816e06f0-ffffffff816e0745: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff817d0a30)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff817d0a30-ffffffff817d0a85: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8180f680)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff8180f680-ffffffff8180f6cf: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81855300)
Location: lib/uuid.c:88
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff81855300-ffffffff8185534f: uuid_is_valid (STB_GLOBAL)
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
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffff80001062d1f8)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffff80001062d1f8-ffff80001062d264: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (c07d3d64)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c07d3d64-c07d3de8: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (c0000000007d01a0)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c0000000007d01a0-c0000000007d025c: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffe00045d0a6)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffe00045d0a6-ffffffe00045d12c: uuid_is_valid (STB_GLOBAL)
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
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8151ba30)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8151ba30-ffffffff8151ba77: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8150bd20)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8150bd20-ffffffff8150bd67: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81517ac0)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81517ac0-ffffffff81517b07: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool uuid_is_valid(const char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81531260)
Location: lib/uuid.c:78
Inline: False
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81531260-ffffffff815312a7: uuid_is_valid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
