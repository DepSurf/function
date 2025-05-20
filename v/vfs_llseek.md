# Function: <code>vfs_llseek</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120ba50)
Location: fs/read_write.c:251
Inline: True
Inline callers:
  - fs/read_write.c:compat_SyS_lseek
  - fs/read_write.c:SyS_llseek
```
**Symbols:**

```
ffffffff8120ba50-ffffffff8120ba80: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812329d9)
Location: fs/read_write.c:292
Inline: True
Inline callers:
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff81231750-ffffffff81231780: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245559)
Location: fs/read_write.c:292
Inline: True
Inline callers:
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff81243d00-ffffffff81243d30: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812509c9)
Location: fs/read_write.c:290
Inline: True
Inline callers:
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff8124f510-ffffffff8124f540: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272889)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812714a0-ffffffff812714d3: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81297544)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812971a0-ffffffff812971d3: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ac1f4)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812abe50-ffffffff812abe83: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c9143)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812c8660-ffffffff812c8693: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dab53)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812da070-ffffffff812da0a3: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131144b)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff81310690-ffffffff813106c3: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131ce7b)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff8131c940-ffffffff8131c973: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81322fed)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff81322ab0-ffffffff81322ae3: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813704dd)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff8136ffa0-ffffffff8136ffd3: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ef013)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff813ee9d0-ffffffff813eea0f: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477abf)
Location: fs/read_write.c:285
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/coredump.c:__dump_skip
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff81477290-ffffffff814772ca: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814acd8f)
Location: fs/read_write.c:285
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/coredump.c:__dump_skip
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff814abbf0-ffffffff814abc2d: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dd85f)
Location: fs/read_write.c:285
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/coredump.c:__dump_skip
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff814dd090-ffffffff814dd0cd: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001038116c)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffff80001037f478-ffff80001037f504: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056bb68)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
c0569c94-c0569cec: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000476150)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
c0000000004752f0-c000000000475374: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025648a)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffe000254f74-ffffffe000254fbe: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3133)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812d2650-ffffffff812d2683: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3db3)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812c32d0-ffffffff812c3303: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d0f43)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812d0460-ffffffff812d0493: vfs_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e1d73)
Location: fs/read_write.c:291
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
```
**Symbols:**

```
ffffffff812e1290-ffffffff812e12c3: vfs_llseek (STB_GLOBAL)
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
