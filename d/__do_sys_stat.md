# Function: <code>__do_sys_stat</code>

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
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f610)
Location: fs/stat.c:244
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff8129f610-ffffffff8129f680: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b45f0)
Location: fs/stat.c:244
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812b45f0-ffffffff812b4660: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1360)
Location: fs/stat.c:246
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812d1360-ffffffff812d13d2: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2ef0)
Location: fs/stat.c:246
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812e2ef0-ffffffff812e2f62: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a8a0)
Location: fs/stat.c:266
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff8131a8a0-ffffffff8131a90d: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325f30)
Location: fs/stat.c:254
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff81325f30-ffffffff81325f9d: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c040)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff8132c040-ffffffff8132c0ad: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813797b0)
Location: fs/stat.c:290
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff813797b0-ffffffff8137981d: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9190)
Location: fs/stat.c:304
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff813f9190-ffffffff813f9215: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482870)
Location: fs/stat.c:319
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff81482870-ffffffff814828f5: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7490)
Location: fs/stat.c:325
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff814b7490-ffffffff814b7515: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9ac0)
Location: fs/stat.c:353
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff814e9ac0-ffffffff814e9b77: __do_sys_stat (STB_LOCAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db4d0)
Location: fs/stat.c:246
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812db4d0-ffffffff812db542: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc150)
Location: fs/stat.c:246
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812cc150-ffffffff812cc1c2: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d92e0)
Location: fs/stat.c:246
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812d92e0-ffffffff812d9352: __do_sys_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_stat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea1f0)
Location: fs/stat.c:246
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_stat
  - fs/stat.c:__x64_sys_stat
```
**Symbols:**

```
ffffffff812ea1f0-ffffffff812ea262: __do_sys_stat (STB_LOCAL)
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
