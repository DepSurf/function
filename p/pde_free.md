# Function: <code>pde_free</code>

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
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320250)
Location: fs/proc/generic.c:36
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81320250-ffffffff813202a3: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337330)
Location: fs/proc/generic.c:36
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81337330-ffffffff81337383: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f450)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8135f450-ffffffff8135f4a7: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813776b0)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813776b0-ffffffff81377707: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0adb)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813c0520-ffffffff813c0579: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d292b)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813d2370-ffffffff813d23c9: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d96ff)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813d9170-ffffffff813d91c9: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142ae2f)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8142a8a0-ffffffff8142a8f9: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4485)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff814a3e70-ffffffff814a3ed0: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815398e5)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81539270-ffffffff815392d0: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571b46)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff815714b0-ffffffff81571510: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa4f6)
Location: fs/proc/generic.c:37
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff815a9e60-ffffffff815a9ec0: pde_free (STB_GLOBAL)
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
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443328)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffff800010443328-ffff80001044338c: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608638)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
c0608638-c0608698: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558970)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
c000000000558970-c000000000558a00: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002d9a62)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffe0002d9a62-ffffffe0002d9ac0: pde_free (STB_GLOBAL)
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
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136fc90)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8136fc90-ffffffff8136fce7: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360720)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81360720-ffffffff81360777: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136d760)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8136d760-ffffffff8136d7b7: pde_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pde_free(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381090)
Location: fs/proc/generic.c:37
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81381090-ffffffff813810e7: pde_free (STB_GLOBAL)
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
