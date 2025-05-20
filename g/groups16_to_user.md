# Function: <code>groups16_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81104529)
Location: kernel/uid16.c:111
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_getgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8110b9e9)
Location: kernel/uid16.c:111
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_getgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81113409)
Location: kernel/uid16.c:111
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_getgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81114939)
Location: kernel/uid16.c:112
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_getgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8111fe89)
Location: kernel/uid16.c:113
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_getgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8112d430)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff8112d430-ffffffff8112d4df: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81138d20)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81138d20-ffffffff81138dcf: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81143f20)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81143f20-ffffffff81143fcf: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8114fa00)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff8114fa00-ffffffff8114faaf: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811601e0)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff811601e0-ffffffff8116028f: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115c170)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff8115c170-ffffffff8115c21f: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115d390)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff8115d390-ffffffff8115d43f: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81182690)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81182690-ffffffff8118273f: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811b8ef0)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff811b8ef0-ffffffff811b8fb4: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811fa3c0)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff811fa3c0-ffffffff811fa484: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8120f780)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff8120f780-ffffffff8120f832: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81226f20)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81226f20-ffffffff81226fd2: groups16_to_user (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffff8000101be374)
Location: kernel/uid16.c:114
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_getgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (c0406314)
Location: kernel/uid16.c:114
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_getgroups16
```
</details>
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
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81148020)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81148020-ffffffff811480cf: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8113b2d0)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff8113b2d0-ffffffff8113b37f: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81145ed0)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81145ed0-ffffffff81145f7f: groups16_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int groups16_to_user(old_gid_t *grouplist, struct group_info *group_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81152ae0)
Location: kernel/uid16.c:114
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_getgroups16
  - kernel/uid16.c:__x64_sys_getgroups16
```
**Symbols:**

```
ffffffff81152ae0-ffffffff81152b8f: groups16_to_user (STB_LOCAL)
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
