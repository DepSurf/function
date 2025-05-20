# Function: <code>groups16_from_user</code>

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
In kernel/uid16.c (ffffffff8110460f)
Location: kernel/uid16.c:129
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_setgroups16
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
In kernel/uid16.c (ffffffff8110bacf)
Location: kernel/uid16.c:129
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_setgroups16
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
In kernel/uid16.c (ffffffff811134e1)
Location: kernel/uid16.c:129
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_setgroups16
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
In kernel/uid16.c (ffffffff81114a08)
Location: kernel/uid16.c:130
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_setgroups16
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
In kernel/uid16.c (ffffffff8111ff58)
Location: kernel/uid16.c:131
Inline: True
Inline callers:
  - kernel/uid16.c:SyS_setgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8112d600)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8112d600-ffffffff8112d6b2: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81138ef0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81138ef0-ffffffff81138fa2: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811440f0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811440f0-ffffffff81144193: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8114fbd0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8114fbd0-ffffffff8114fc73: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811603b0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811603b0-ffffffff81160453: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115c340)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8115c340-ffffffff8115c3e3: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115d560)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8115d560-ffffffff8115d603: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81182860)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81182860-ffffffff81182903: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811b9100)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811b9100-ffffffff811b91d9: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811fa630)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811fa630-ffffffff811fa709: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8120f9e0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8120f9e0-ffffffff8120faa6: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff812276f1)
Location: kernel/uid16.c:132
Inline: True
Inline callers:
  - kernel/uid16.c:__do_sys_setgroups16
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
In kernel/uid16.c (ffff8000101be088)
Location: kernel/uid16.c:132
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
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
In kernel/uid16.c (c0406438)
Location: kernel/uid16.c:132
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_setgroups16
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
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811481f0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811481f0-ffffffff81148293: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8113b4a0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8113b4a0-ffffffff8113b543: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811460a0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811460a0-ffffffff81146143: groups16_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int groups16_from_user(struct group_info *group_info, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81152cb0)
Location: kernel/uid16.c:132
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81152cb0-ffffffff81152d53: groups16_from_user (STB_LOCAL)
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
