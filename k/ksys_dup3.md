# Function: <code>ksys_dup3</code>

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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bbf90)
Location: fs/file.c:874
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812bbf90-ffffffff812bc089: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1180)
Location: fs/file.c:904
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812d1180-ffffffff812d1279: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee190)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812ee190-ffffffff812ee294: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ffc50)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812ffc50-ffffffff812ffd54: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338d90)
Location: fs/file.c:935
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff81338d90-ffffffff81338e94: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813449a0)
Location: fs/file.c:1127
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff813449a0-ffffffff81344aa5: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134aed0)
Location: fs/file.c:1138
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff8134aed0-ffffffff8134afd5: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398d30)
Location: fs/file.c:1204
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff81398d30-ffffffff81398e35: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141b5a0)
Location: fs/file.c:1206
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff8141b5a0-ffffffff8141b6c8: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a7690)
Location: fs/file.c:1216
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff814a7690-ffffffff814a77b8: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc670)
Location: fs/file.c:1231
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff814dc670-ffffffff814dc798: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150e8a0)
Location: fs/file.c:1355
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff8150e8a0-ffffffff8150e9c3: ksys_dup3 (STB_LOCAL)
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b1798)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__arm64_sys_dup2
  - fs/file.c:__arm64_sys_dup3
```
**Symbols:**

```
ffff8000103b1798-ffff8000103b18dc: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590b90)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:__se_sys_dup3
```
**Symbols:**

```
c0590b90-c0590ca0: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004acde0)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:__se_sys_dup3
```
**Symbols:**

```
c0000000004acde0-c0000000004acf78: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000275850)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:__se_sys_dup3
```
**Symbols:**

```
ffffffe000275850-ffffffe000275970: ksys_dup3 (STB_LOCAL)
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8230)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812f8230-ffffffff812f8334: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8e50)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812e8e50-ffffffff812e8f54: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6040)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff812f6040-ffffffff812f6144: ksys_dup3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307150)
Location: fs/file.c:910
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__ia32_sys_dup3
  - fs/file.c:__x64_sys_dup3
```
**Symbols:**

```
ffffffff81307150-ffffffff81307263: ksys_dup3 (STB_LOCAL)
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
