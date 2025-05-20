# Function: <code>shmem_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ab8b0)
Location: mm/shmem.c:1392
Inline: False
Direct callers:
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff811ab8b0-ffffffff811ab95b: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c41e0)
Location: mm/shmem.c:2043
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff811c41e0-ffffffff811c42a7: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d42e0)
Location: mm/shmem.c:2080
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff811d42e0-ffffffff811d43a7: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dca70)
Location: mm/shmem.c:2117
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff811dca70-ffffffff811dcb37: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2920)
Location: mm/shmem.c:2128
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff811f2920-ffffffff811f29e7: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213d80)
Location: mm/shmem.c:2147
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81213d80-ffffffff81213e47: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81226d40)
Location: mm/shmem.c:2109
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81226d40-ffffffff81226e07: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812368b0)
Location: mm/shmem.c:2171
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff812368b0-ffffffff81236970: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244af0)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81244af0-ffffffff81244bb0: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812727b0)
Location: mm/shmem.c:2166
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff812727b0-ffffffff81272866: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127cc70)
Location: mm/shmem.c:2228
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8127cc70-ffffffff8127cd26: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281e10)
Location: mm/shmem.c:2230
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81281e10-ffffffff81281ec6: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bfd50)
Location: mm/shmem.c:2232
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff812bfd50-ffffffff812bfe0c: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131c640)
Location: mm/shmem.c:2231
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8131c640-ffffffff8131c6da: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813902a0)
Location: mm/shmem.c:2251
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813902a0-ffffffff8139033a: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813c2c00)
Location: mm/shmem.c:2281
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813c2c00-ffffffff813c2c97: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813ed890)
Location: mm/shmem.c:2372
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813ed890-ffffffff813ed930: shmem_lock (STB_GLOBAL)
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
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d70a8)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffff8000102d70a8-ffff8000102d721c: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fef68)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
c04fef68-c04ff050: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003972d0)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
c0000000003972d0-c00000000039745c: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f23f6)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffe0001f23f6-ffffffe0001f24f4: shmem_lock (STB_GLOBAL)
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
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d140)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8123d140-ffffffff8123d200: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230140)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81230140-ffffffff812301f7: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123aee0)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8123aee0-ffffffff8123afa0: shmem_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_lock(struct file *file, int lock, struct user_struct *user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124a5f0)
Location: mm/shmem.c:2188
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8124a5f0-ffffffff8124a6a4: shmem_lock (STB_GLOBAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucounts *ucounts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_struct *user</code>
</li>
</ul>
</details>
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
