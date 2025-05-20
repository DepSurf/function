# Function: <code>set_current_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a4580)
Location: kernel/groups.c:176
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810a4580-ffffffff810a45bb: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a7c80)
Location: kernel/groups.c:176
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810a7c80-ffffffff810a7cbb: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810adcb0)
Location: kernel/groups.c:151
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810adcb0-ffffffff810adceb: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa7e0)
Location: kernel/groups.c:138
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810aa7e0-ffffffff810aa81b: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b14c0)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810b14c0-ffffffff810b14fb: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b82c0)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810b82c0-ffffffff810b82fb: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c13a0)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c13a0-ffffffff810c13db: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c7490)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c7490-ffffffff810c74cd: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d0560)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d0560-ffffffff810d059d: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da776)
Location: kernel/groups.c:139
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810da3a0-ffffffff810da3dd: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5ed6)
Location: kernel/groups.c:139
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d5b00-ffffffff810d5b3d: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7bc1)
Location: kernel/groups.c:134
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d77c0-ffffffff810d77fd: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb471)
Location: kernel/groups.c:134
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810eb070-ffffffff810eb0ad: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8110639e)
Location: kernel/groups.c:134
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81105f30-ffffffff81105f73: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112baf0)
Location: kernel/groups.c:134
Inline: False
Direct callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8112baf0-ffffffff8112bb7f: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138950)
Location: kernel/groups.c:134
Inline: False
Direct callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81138950-ffffffff811389df: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143840)
Location: kernel/groups.c:134
Inline: False
Direct callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:__do_sys_setgroups16
```
**Symbols:**

```
ffffffff81143840-ffffffff811438cf: set_current_groups (STB_GLOBAL)
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
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff8000101311a0)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/uid16.c:__arm64_sys_setgroups16
```
**Symbols:**

```
ffff8000101311a0-ffff8000101311e8: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c03804dc)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/uid16.c:__se_sys_setgroups16
```
**Symbols:**

```
c03804dc-c038051c: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a440)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
```
**Symbols:**

```
c00000000017a440-c00000000017a4ac: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e404a)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
```
**Symbols:**

```
ffffffe0000e404a-ffffffe0000e40ae: set_current_groups (STB_GLOBAL)
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
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca8e0)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810ca8e0-ffffffff810ca91d: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b90f0)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810b90f0-ffffffff810b912d: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c9e10)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c9e10-ffffffff810c9e4d: set_current_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_current_groups(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d2360)
Location: kernel/groups.c:139
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d2360-ffffffff810d239d: set_current_groups (STB_GLOBAL)
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
