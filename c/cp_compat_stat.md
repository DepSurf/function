# Function: <code>cp_compat_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263300)
Location: fs/compat.c:129
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_newstat
  - fs/compat.c:C_SYSC_newlstat
  - fs/compat.c:C_SYSC_newfstatat
  - fs/compat.c:C_SYSC_newfstat
```
**Symbols:**

```
ffffffff81263300-ffffffff812634e0: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128f550)
Location: fs/compat.c:129
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_newfstat
  - fs/compat.c:C_SYSC_newfstatat
  - fs/compat.c:C_SYSC_newlstat
  - fs/compat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff8128f550-ffffffff8128f730: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4540)
Location: fs/compat.c:115
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_newfstat
  - fs/compat.c:C_SYSC_newfstatat
  - fs/compat.c:C_SYSC_newlstat
  - fs/compat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff812a4540-ffffffff812a4720: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81257170)
Location: fs/stat.c:580
Inline: False
Direct callers:
  - fs/stat.c:C_SYSC_newfstat
  - fs/stat.c:C_SYSC_newfstatat
  - fs/stat.c:C_SYSC_newlstat
  - fs/stat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff81257170-ffffffff81257361: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812793c0)
Location: fs/stat.c:581
Inline: False
Direct callers:
  - fs/stat.c:C_SYSC_newfstat
  - fs/stat.c:C_SYSC_newfstatat
  - fs/stat.c:C_SYSC_newlstat
  - fs/stat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff812793c0-ffffffff812795b1: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129ff00)
Location: fs/stat.c:587
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff8129ff00-ffffffff812a00e6: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4ee0)
Location: fs/stat.c:590
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812b4ee0-ffffffff812b50c6: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1c80)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812d1c80-ffffffff812d1e58: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3810)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812e3810-ffffffff812e39e8: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a3d0)
Location: fs/stat.c:619
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff8131a3d0-ffffffff8131a5a8: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325a60)
Location: fs/stat.c:607
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff81325a60-ffffffff81325c38: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132bb90)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff8132bb90-ffffffff8132bd65: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379300)
Location: fs/stat.c:643
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff81379300-ffffffff813794d5: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f87c0)
Location: fs/stat.c:663
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff813f87c0-ffffffff813f899b: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81481d30)
Location: fs/stat.c:680
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff81481d30-ffffffff81481f0b: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6940)
Location: fs/stat.c:693
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff814b6940-ffffffff814b6b1b: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e8c70)
Location: fs/stat.c:715
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff814e8c70-ffffffff814e8e4b: cp_compat_stat (STB_LOCAL)
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
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038ac10)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffff80001038ac10-ffff80001038ae14: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0000000004826b0)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
c0000000004826b0-c0000000004828c4: cp_compat_stat (STB_LOCAL)
```
</details>
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
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dbdf0)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812dbdf0-ffffffff812dbfc8: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cca70)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812cca70-ffffffff812ccc48: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9c00)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812d9c00-ffffffff812d9dd8: cp_compat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cp_compat_stat(struct kstat *stat, struct compat_stat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eab10)
Location: fs/stat.c:592
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
```
**Symbols:**

```
ffffffff812eab10-ffffffff812eace8: cp_compat_stat (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
