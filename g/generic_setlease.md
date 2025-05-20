# Function: <code>generic_setlease</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81261ec0)
Location: fs/locks.c:1756
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff81261ec0-ffffffff812624f5: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128de10)
Location: fs/locks.c:1782
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff8128de10-ffffffff8128e3de: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a1ce0)
Location: fs/locks.c:1820
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff812a1ce0-ffffffff812a2359: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0aa0)
Location: fs/locks.c:1820
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff812b0aa0-ffffffff812b105b: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d4540)
Location: fs/locks.c:1830
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff812d4540-ffffffff812d4b31: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812feb80)
Location: fs/locks.c:1828
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff812feb80-ffffffff812ff191: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813145d0)
Location: fs/locks.c:1944
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff813145d0-ffffffff81314c43: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133bf10)
Location: fs/locks.c:1962
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff8133bf10-ffffffff8133c53a: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81354450)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff81354450-ffffffff81354a7a: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139b610)
Location: fs/locks.c:1993
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8139b610-ffffffff8139b6f6: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ad040)
Location: fs/locks.c:1994
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff813ad040-ffffffff813ad126: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b49f0)
Location: fs/locks.c:1997
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff813b49f0-ffffffff813b4cb4: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814046f0)
Location: fs/locks.c:1900
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff814046f0-ffffffff814049b4: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81479cc0)
Location: fs/locks.c:1875
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81479cc0-ffffffff81479fe0: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c670)
Location: fs/locks.c:1861
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8150c670-ffffffff8150c990: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81543df0)
Location: fs/locks.c:1862
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81543df0-ffffffff8154412e: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_setlease(struct file *filp, int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815792d0)
Location: fs/locks.c:1869
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff815792d0-ffffffff81579609: generic_setlease (STB_GLOBAL)
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
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010417288)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffff800010417288-ffff800010417994: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e416c)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
c05e416c-c05e4860: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000526da0)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
c000000000526da0-c0000000005275a0: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bdc0a)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffe0002bdc0a-ffffffe0002be166: generic_setlease (STB_GLOBAL)
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
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134ca30)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff8134ca30-ffffffff8134d05a: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d710)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff8133d710-ffffffff8133dd3a: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a500)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff8134a500-ffffffff8134ab2a: generic_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int generic_setlease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135eda0)
Location: fs/locks.c:1990
Inline: True
Direct callers:
  - fs/locks.c:vfs_setlease
```
**Symbols:**

```
ffffffff8135eda0-ffffffff8135f42c: generic_setlease (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int arg</code> ➡️ <code>int arg</code>
</li>
</ul>
</details>
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
