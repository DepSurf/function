# Function: <code>security_file_set_fowner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133dfd0)
Location: security/security.c:830
Inline: False
Direct callers:
  - fs/fcntl.c:f_setown
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8133dfd0-ffffffff8133e006: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373630)
Location: security/security.c:852
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81373630-ffffffff81373666: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389f60)
Location: security/security.c:873
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81389f60-ffffffff81389f96: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f360)
Location: security/security.c:1485
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff8139f360-ffffffff8139f396: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4ec0)
Location: security/security.c:1443
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff813c4ec0-ffffffff813c4efc: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5140)
Location: security/security.c:969
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff813f5140-ffffffff813f5174: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410580)
Location: security/security.c:1505
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81410580-ffffffff814105b4: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dcf0)
Location: security/security.c:1524
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff8143dcf0-ffffffff8143dd26: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814577c0)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814577c0-ffffffff814577f4: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa5c0)
Location: security/security.c:1739
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814aa5c0-ffffffff814aa5f4: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7bd0)
Location: security/security.c:1741
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814c7bd0-ffffffff814c7c04: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce200)
Location: security/security.c:1791
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814ce200-ffffffff814ce234: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526fb0)
Location: security/security.c:1799
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81526fb0-ffffffff81526fe4: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bbc00)
Location: security/security.c:1804
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff815bbc00-ffffffff815bbc3c: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667a20)
Location: security/security.c:1846
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81667a20-ffffffff81667a5c: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0040)
Location: security/security.c:2905
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff816a0040-ffffffff816a007c: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc930)
Location: security/security.c:2983
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff816dc930-ffffffff816dc96c: security_file_set_fowner (STB_GLOBAL)
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
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543418)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffff800010543418-ffff800010543460: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9374)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
c06f9374-c06f93bc: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697390)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
c000000000697390-c000000000697408: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f984)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffe00039f984-ffffffe00039f9bc: security_file_set_fowner (STB_GLOBAL)
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
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144fda0)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff8144fda0-ffffffff8144fdd4: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814407f0)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814407f0-ffffffff81440824: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144be40)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff8144be40-ffffffff8144be74: security_file_set_fowner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_file_set_fowner(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463210)
Location: security/security.c:1563
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81463210-ffffffff81463244: security_file_set_fowner (STB_GLOBAL)
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
