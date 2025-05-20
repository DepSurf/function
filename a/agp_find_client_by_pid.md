# Function: <code>agp_find_client_by_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8151b792)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_ioctl
```
**Symbols:**

```
ffffffff8151bd70-ffffffff8151bda3: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8156f2e4)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
```
**Symbols:**

```
ffffffff8156eab0-ffffffff8156eae3: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8159b9a4)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
```
**Symbols:**

```
ffffffff8159b170-ffffffff8159b1a3: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff815af830)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
```
**Symbols:**

```
ffffffff815af1d0-ffffffff815af203: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816163a0)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
```
**Symbols:**

```
ffffffff81615d40-ffffffff81615d73: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff81650199)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8164fab0-ffffffff8164fae3: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8166e339)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8166dc60-ffffffff8166dc8f: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816a31c4)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816a3800-ffffffff816a382f: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816c6c4e)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816c6590-ffffffff816c65bf: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8177aac4)
Location: drivers/char/agp/frontend.c:486
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
```
**Symbols:**

```
ffffffff8177afa0-ffffffff8177afcf: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (c000000000952fa0)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
```
**Symbols:**

```
c0000000009533a0-c0000000009533f0: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8168c69e)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8168bfe0-ffffffff8168c00f: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8166a09e)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816699e0-ffffffff81669a0f: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816ba90e)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816ba250-ffffffff816ba27f: agp_find_client_by_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct agp_client *agp_find_client_by_pid(pid_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816d4ede)
Location: drivers/char/agp/frontend.c:488
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_mmap
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816d4820-ffffffff816d484f: agp_find_client_by_pid (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
