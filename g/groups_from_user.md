# Function: <code>groups_from_user</code>

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
In kernel/groups.c (ffffffff810a477f)
Location: kernel/groups.c:81
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
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
In kernel/groups.c (ffffffff810a7e8f)
Location: kernel/groups.c:81
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
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
In kernel/groups.c (ffffffff810ade8f)
Location: kernel/groups.c:57
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
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
In kernel/groups.c (ffffffff810aa9b8)
Location: kernel/groups.c:58
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
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
In kernel/groups.c (ffffffff810b1698)
Location: kernel/groups.c:59
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int groups_from_user(struct group_info *group_info, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8400)
Location: kernel/groups.c:59
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
**Symbols:**

```
ffffffff810b8400-ffffffff810b84a6: groups_from_user (STB_LOCAL)
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
In kernel/groups.c (ffffffff810c161a)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffff810c770b)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffff810d07db)
Location: kernel/groups.c:59
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da6e5)
Location: kernel/groups.c:59
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5e45)
Location: kernel/groups.c:59
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7b29)
Location: kernel/groups.c:54
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb3d9)
Location: kernel/groups.c:54
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81106300)
Location: kernel/groups.c:54
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bf4d)
Location: kernel/groups.c:54
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138dad)
Location: kernel/groups.c:54
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
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
In kernel/groups.c (ffffffff81143aed)
Location: kernel/groups.c:54
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
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
int groups_from_user(struct group_info *group_info, gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010130f20)
Location: kernel/groups.c:59
Inline: False
Direct callers:
  - kernel/groups.c:__arm64_sys_setgroups
```
**Symbols:**

```
ffff800010130f20-ffff80001013110c: groups_from_user (STB_LOCAL)
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
In kernel/groups.c (c03806e8)
Location: kernel/groups.c:59
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
In kernel/groups.c (c00000000017a7f4)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffe0000e4274)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffff810cab5b)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffff810b936b)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffff810ca08b)
Location: kernel/groups.c:59
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
In kernel/groups.c (ffffffff810d25db)
Location: kernel/groups.c:59
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
</ul>
<b>Arch</b>
<ul>
</ul>
