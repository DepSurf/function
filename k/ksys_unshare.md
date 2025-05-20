# Function: <code>ksys_unshare</code>

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
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108de00)
Location: kernel/fork.c:2402
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff8108de00-ffffffff8108e18c: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096090)
Location: kernel/fork.c:2510
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff81096090-ffffffff8109641c: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a5c0)
Location: kernel/fork.c:2801
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff8109a5c0-ffffffff8109a95e: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0b80)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff810a0b80-ffffffff810a0f1e: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a79f0)
Location: kernel/fork.c:2943
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff810a79f0-ffffffff810a7d7f: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3760)
Location: kernel/fork.c:2923
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff810a3760-ffffffff810a3af7: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4390)
Location: kernel/fork.c:2955
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff810a4390-ffffffff810a4745: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5bb0)
Location: kernel/fork.c:3048
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff810b5bb0-ffffffff810b5f65: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cc0a0)
Location: kernel/fork.c:3125
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff810cc0a0-ffffffff810cc48e: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e9750)
Location: kernel/fork.c:3161
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff810e9750-ffffffff810e9b3e: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f5360)
Location: kernel/fork.c:3397
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff810f5360-ffffffff810f5734: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fe700)
Location: kernel/fork.c:3387
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff810fe700-ffffffff810feae9: ksys_unshare (STB_GLOBAL)
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
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f5568)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__arm64_sys_unshare
```
**Symbols:**

```
ffff8000100f5568-ffff8000100f5904: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0353c78)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_unshare
```
**Symbols:**

```
c0353c78-c0354088: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b640)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_unshare
```
**Symbols:**

```
c00000000013b640-c00000000013baac: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c1956)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_unshare
```
**Symbols:**

```
ffffffe0000c1956-ffffffe0000c1c48: ksys_unshare (STB_GLOBAL)
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
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a4a0)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff8109a4a0-ffffffff8109a83e: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088ee0)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff81088ee0-ffffffff8108927e: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a450)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff8109a450-ffffffff8109a7ee: ksys_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_unshare(long unsigned int unshare_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a20d0)
Location: kernel/fork.c:2818
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
**Symbols:**

```
ffffffff810a20d0-ffffffff810a246a: ksys_unshare (STB_GLOBAL)
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
