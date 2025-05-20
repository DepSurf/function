# Function: <code>cp_old_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211680)
Location: fs/stat.c:140
Inline: False
Direct callers:
  - fs/stat.c:SYSC_stat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_fstat
```
**Symbols:**

```
ffffffff81211680-ffffffff81211866: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81238130)
Location: fs/stat.c:140
Inline: False
Direct callers:
  - fs/stat.c:SYSC_fstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
```
**Symbols:**

```
ffffffff81238130-ffffffff81238316: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124adf0)
Location: fs/stat.c:140
Inline: False
Direct callers:
  - fs/stat.c:SYSC_fstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
```
**Symbols:**

```
ffffffff8124adf0-ffffffff8124afd6: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812568c0)
Location: fs/stat.c:206
Inline: False
Direct callers:
  - fs/stat.c:SYSC_fstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
```
**Symbols:**

```
ffffffff812568c0-ffffffff81256a99: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81278b10)
Location: fs/stat.c:207
Inline: False
Direct callers:
  - fs/stat.c:SYSC_fstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
```
**Symbols:**

```
ffffffff81278b10-ffffffff81278ce9: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:207
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff8129f460-ffffffff8129f60e: cp_old_stat (STB_LOCAL)
ffffffff812a0656-ffffffff812a0680: cp_old_stat.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:207
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812b4440-ffffffff812b45ee: cp_old_stat (STB_LOCAL)
ffffffff812b5636-ffffffff812b5660: cp_old_stat.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:209
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812d11b0-ffffffff812d135f: cp_old_stat (STB_LOCAL)
ffffffff812d23e6-ffffffff812d2410: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:209
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812e2d40-ffffffff812e2eef: cp_old_stat (STB_LOCAL)
ffffffff812e3f76-ffffffff812e3fa0: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:229
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff81319ee0-ffffffff8131a08d: cp_old_stat (STB_LOCAL)
ffffffff8131b318-ffffffff8131b342: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:217
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff81325570-ffffffff8132571d: cp_old_stat (STB_LOCAL)
ffffffff81bea608-ffffffff81bea632: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:235
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff8132b6b0-ffffffff8132b85a: cp_old_stat (STB_LOCAL)
ffffffff81bdc644-ffffffff81bdc66e: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:253
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff81378e20-ffffffff81378fca: cp_old_stat (STB_LOCAL)
ffffffff81cc399e-ffffffff81cc39c8: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:267
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff813f8290-ffffffff813f846a: cp_old_stat (STB_LOCAL)
ffffffff81e76115-ffffffff81e7613f: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81481780)
Location: fs/stat.c:282
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff81481780-ffffffff81481994: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6380)
Location: fs/stat.c:288
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff814b6380-ffffffff814b6594: cp_old_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e86b0)
Location: fs/stat.c:316
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff814e86b0-ffffffff814e88c4: cp_old_stat (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:209
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812db320-ffffffff812db4cf: cp_old_stat (STB_LOCAL)
ffffffff812dc556-ffffffff812dc580: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:209
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812cbfa0-ffffffff812cc14f: cp_old_stat (STB_LOCAL)
ffffffff812cd1d6-ffffffff812cd200: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:209
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812d9130-ffffffff812d92df: cp_old_stat (STB_LOCAL)
ffffffff812da366-ffffffff812da390: cp_old_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cp_old_stat(struct kstat *stat, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:209
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812ea040-ffffffff812ea1ef: cp_old_stat (STB_LOCAL)
ffffffff812eb191-ffffffff812eb1bb: cp_old_stat.cold (STB_LOCAL)
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
