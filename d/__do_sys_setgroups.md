# Function: <code>__do_sys_setgroups</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b85c8)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c15ee)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c76dd)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d07ad)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da660)
Location: kernel/groups.c:190
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff810da660-ffffffff810da7c8: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5dc0)
Location: kernel/groups.c:190
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff810d5dc0-ffffffff810d5f28: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7a80)
Location: kernel/groups.c:185
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff810d7a80-ffffffff810d7c13: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb330)
Location: kernel/groups.c:185
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff810eb330-ffffffff810eb4c3: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81106250)
Location: kernel/groups.c:185
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff81106250-ffffffff811063f4: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bea0)
Location: kernel/groups.c:198
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff8112bea0-ffffffff8112c06d: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138d00)
Location: kernel/groups.c:198
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff81138d00-ffffffff81138ecd: __do_sys_setgroups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143a40)
Location: kernel/groups.c:198
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff81143a40-ffffffff81143c57: __do_sys_setgroups (STB_LOCAL)
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
In kernel/groups.c (ffff8000101312e0)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__arm64_sys_setgroups
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
In kernel/groups.c (c03806bc)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a7c8)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e4254)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810cab2d)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b933d)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca05d)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d25ad)
Location: kernel/groups.c:190
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
