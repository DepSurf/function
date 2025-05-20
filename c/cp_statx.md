# Function: <code>cp_statx</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81256f30)
Location: fs/stat.c:515
Inline: False
Direct callers:
  - fs/stat.c:SYSC_statx
```
**Symbols:**

```
ffffffff81256f30-ffffffff812570e3: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81279180)
Location: fs/stat.c:516
Inline: False
Direct callers:
  - fs/stat.c:SYSC_statx
```
**Symbols:**

```
ffffffff81279180-ffffffff81279333: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129fc60)
Location: fs/stat.c:522
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff8129fc60-ffffffff8129fe13: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4c40)
Location: fs/stat.c:525
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812b4c40-ffffffff812b4df3: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d19f0)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812d19f0-ffffffff812d1b93: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3580)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812e3580-ffffffff812e3723: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a210)
Location: fs/stat.c:547
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff8131a210-ffffffff8131a3c1: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813258a0)
Location: fs/stat.c:535
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff813258a0-ffffffff81325a51: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132b9e0)
Location: fs/stat.c:553
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff8132b9e0-ffffffff8132bb8e: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379150)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff81379150-ffffffff813792fe: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f85f0)
Location: fs/stat.c:584
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff813f85f0-ffffffff813f87bc: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81481b40)
Location: fs/stat.c:599
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff81481b40-ffffffff81481d1a: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6740)
Location: fs/stat.c:605
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff814b6740-ffffffff814b6929: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e8a70)
Location: fs/stat.c:627
Inline: False
Direct callers:
  - fs/stat.c:do_statx
```
**Symbols:**

```
ffffffff814e8a70-ffffffff814e8c59: cp_statx (STB_LOCAL)
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
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038b8a8)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffff80001038b8a8-ffff80001038ba14: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c05731c0)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
c05731c0-c0573384: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000482430)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
c000000000482430-c0000000004825d0: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c92a)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffe00025c92a-ffffffe00025ca54: cp_statx (STB_LOCAL)
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
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dbb60)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812dbb60-ffffffff812dbd03: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc7e0)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812cc7e0-ffffffff812cc983: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9970)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812d9970-ffffffff812d9b13: cp_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cp_statx(const struct kstat *stat, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea880)
Location: fs/stat.c:527
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_statx
```
**Symbols:**

```
ffffffff812ea880-ffffffff812eaa23: cp_statx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
