# Function: <code>vfs_setlease</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81262500)
Location: fs/locks.c:1805
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81262500-ffffffff81262524: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128e3e0)
Location: fs/locks.c:1831
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8128e3e0-ffffffff8128e404: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2360)
Location: fs/locks.c:1869
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff812a2360-ffffffff812a2393: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b1060)
Location: fs/locks.c:1869
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff812b1060-ffffffff812b1093: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d4b40)
Location: fs/locks.c:1879
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff812d4b40-ffffffff812d4b76: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ff1a0)
Location: fs/locks.c:1877
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff812ff1a0-ffffffff812ff1d6: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81314c50)
Location: fs/locks.c:1993
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81314c50-ffffffff81314c77: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c540)
Location: fs/locks.c:2011
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8133c540-ffffffff8133c567: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81354a80)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81354a80-ffffffff81354af7: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139da18)
Location: fs/locks.c:2100
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8139b700-ffffffff8139b777: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af3c8)
Location: fs/locks.c:2101
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff813ad130-ffffffff813ad1a7: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b6688)
Location: fs/locks.c:2104
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff813b4cc0-ffffffff813b4d37: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81406388)
Location: fs/locks.c:2007
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff814049c0-ffffffff81404a37: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147ae67)
Location: fs/locks.c:1982
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81479fe0-ffffffff8147a06c: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150d9a7)
Location: fs/locks.c:1968
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8150c9a0-ffffffff8150ca2c: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81545177)
Location: fs/locks.c:1945
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81544140-ffffffff815441cf: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_setlease(struct file *filp, int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a666)
Location: fs/locks.c:1952
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlease
Direct callers:
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff81579620-ffffffff815796b5: vfs_setlease (STB_GLOBAL)
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
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010417998)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffff800010417998-ffff800010417a44: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e4860)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
c05e4860-c05e48d4: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005275a0)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
c0000000005275a0-c000000000527684: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002be166)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffe0002be166-ffffffe0002be1ee: vfs_setlease (STB_GLOBAL)
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
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134d060)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8134d060-ffffffff8134d0d7: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133dd40)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8133dd40-ffffffff8133ddb7: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134ab30)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8134ab30-ffffffff8134aba7: vfs_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_setlease(struct file *filp, long int arg, struct file_lock **lease, void **priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135f430)
Location: fs/locks.c:2097
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
```
**Symbols:**

```
ffffffff8135f430-ffffffff8135f4a7: vfs_setlease (STB_GLOBAL)
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
