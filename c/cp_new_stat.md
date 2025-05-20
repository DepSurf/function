# Function: <code>cp_new_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211990)
Location: fs/stat.c:229
Inline: False
Direct callers:
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newfstat
```
**Symbols:**

```
ffffffff81211990-ffffffff81211b10: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81238440)
Location: fs/stat.c:229
Inline: False
Direct callers:
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
```
**Symbols:**

```
ffffffff81238440-ffffffff812385bc: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124b100)
Location: fs/stat.c:229
Inline: False
Direct callers:
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
```
**Symbols:**

```
ffffffff8124b100-ffffffff8124b27c: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81256bf0)
Location: fs/stat.c:295
Inline: False
Direct callers:
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
```
**Symbols:**

```
ffffffff81256bf0-ffffffff81256d6f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81278e40)
Location: fs/stat.c:296
Inline: False
Direct callers:
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
```
**Symbols:**

```
ffffffff81278e40-ffffffff81278fbf: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f820)
Location: fs/stat.c:296
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff8129f820-ffffffff8129f99f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4800)
Location: fs/stat.c:298
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812b4800-ffffffff812b497f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1590)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812d1590-ffffffff812d170f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3120)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812e3120-ffffffff812e329f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a090)
Location: fs/stat.c:320
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff8131a090-ffffffff8131a20f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325720)
Location: fs/stat.c:308
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff81325720-ffffffff8132589f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132b860)
Location: fs/stat.c:326
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff8132b860-ffffffff8132b9dc: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81378fd0)
Location: fs/stat.c:344
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff81378fd0-ffffffff8137914c: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8470)
Location: fs/stat.c:355
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff813f8470-ffffffff813f85ee: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814819b0)
Location: fs/stat.c:370
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff814819b0-ffffffff81481b2e: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b65b0)
Location: fs/stat.c:376
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff814b65b0-ffffffff814b672e: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e88e0)
Location: fs/stat.c:398
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff814e88e0-ffffffff814e8a5e: cp_new_stat (STB_LOCAL)
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
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038b098)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffff80001038b098-ffff80001038b214: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c05728fc)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
c05728fc-c0572b78: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481b90)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
c000000000481b90-c000000000481d20: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c6dc)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffe00025c6dc-ffffffe00025c822: cp_new_stat (STB_LOCAL)
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
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db700)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812db700-ffffffff812db87f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc380)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812cc380-ffffffff812cc4ff: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9510)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812d9510-ffffffff812d968f: cp_new_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cp_new_stat(struct kstat *stat, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea420)
Location: fs/stat.c:300
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffff812ea420-ffffffff812ea59f: cp_new_stat (STB_LOCAL)
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
