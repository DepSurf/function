# Function: <code>ksys_semget</code>

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
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dca30)
Location: ipc/sem.c:586
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813dca30-ffffffff813dcaad: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f7050)
Location: ipc/sem.c:585
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f7050-ffffffff813f70cd: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814238e0)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814238e0-ffffffff8142395e: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143d620)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143d620-ffffffff8143d69e: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148a21d)
Location: ipc/sem.c:600
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8148e200-ffffffff8148e27e: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a7848)
Location: ipc/sem.c:599
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ab940-ffffffff814ab9bd: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814ad788)
Location: ipc/sem.c:599
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b17d0-ffffffff814b184d: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81505c68)
Location: ipc/sem.c:602
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81508de0-ffffffff81508e5d: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81597a28)
Location: ipc/sem.c:602
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159a9c0-ffffffff8159aa58: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81640be8)
Location: ipc/sem.c:602
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81643cf0-ffffffff81643d88: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81679238)
Location: ipc/sem.c:602
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8167c230-ffffffff8167c2c8: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b5628)
Location: ipc/sem.c:602
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b8600-ffffffff816b8698: ksys_semget (STB_GLOBAL)
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
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010525420)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__arm64_sys_semget
```
**Symbols:**

```
ffff800010525420-ffff8000105254c0: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06df8f8)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semget
```
**Symbols:**

```
c06df8f8-c06df9a4: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066f780)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c00000000066f780-c00000000066f838: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe00038992a)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semget
```
**Symbols:**

```
ffffffe00038992a-ffffffe000389990: ksys_semget (STB_GLOBAL)
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
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81435c00)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81435c00-ffffffff81435c7e: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81426680)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426680-ffffffff814266fe: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81431da0)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81431da0-ffffffff81431e1e: ksys_semget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int ksys_semget(key_t key, int nsems, int semflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81448e70)
Location: ipc/sem.c:581
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81448e70-ffffffff81448eee: ksys_semget (STB_GLOBAL)
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
