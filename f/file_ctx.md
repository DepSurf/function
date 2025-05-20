# Function: <code>file_ctx</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145e75d)
Location: security/apparmor/include/file.h:35
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81462459)
Location: security/apparmor/include/file.h:35
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148bc5d)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8148f729)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a5b1d)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814a95e9)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8150272e)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81507005)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8151f0e0)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8152410a)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff815258c4)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8152a2fa)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81583b54)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8158869a)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81624826)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81628c95)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d778e)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff816dd515)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81712569)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81716b25)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81750239)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81755685)
Location: security/apparmor/include/file.h:32
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059bf24)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffff80001059ffcc)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074d4ec)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (c0750c44)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000713ec0)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (c00000000071a10c)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7bd8)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffe0003eb086)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149e0fd)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814a1bc9)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148eb1d)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814925e9)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149a19d)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8149dc69)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b22cd)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814b6240)
Location: security/apparmor/include/file.h:31
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
</ul>

## Differences
