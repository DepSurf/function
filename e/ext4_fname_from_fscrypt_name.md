# Function: <code>ext4_fname_from_fscrypt_name</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac9c4)
Location: fs/ext4/ext4.h:2316
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c5904)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411d54)
Location: fs/ext4/ext4.h:2472
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814251f4)
Location: fs/ext4/ext4.h:2604
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142bf00)
Location: fs/ext4/ext4.h:2656
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
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
In fs/ext4/namei.c (ffffffff8147fda0)
Location: fs/ext4/ext4.h:2726
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fname_from_fscrypt_name(struct ext4_filename *dst, const struct fscrypt_name *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8153c760)
Location: fs/ext4/crypto.c:10
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff8153c760-ffffffff8153c7dd: ext4_fname_from_fscrypt_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fname_from_fscrypt_name(struct ext4_filename *dst, const struct fscrypt_name *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff815daec0)
Location: fs/ext4/crypto.c:10
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff815daec0-ffffffff815daf3d: ext4_fname_from_fscrypt_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fname_from_fscrypt_name(struct ext4_filename *dst, const struct fscrypt_name *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff81612970)
Location: fs/ext4/crypto.c:10
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff81612970-ffffffff816129ed: ext4_fname_from_fscrypt_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fname_from_fscrypt_name(struct ext4_filename *dst, const struct fscrypt_name *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8164b6f0)
Location: fs/ext4/crypto.c:10
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff8164b6f0-ffffffff8164b76d: ext4_fname_from_fscrypt_name (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d400)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0661938)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c889c)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe0003201d8)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bdee4)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ae974)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
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
In fs/ext4/namei.c (ffffffff813b97bd)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0474)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
