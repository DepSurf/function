# Function: <code>groups_to_user</code>

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
In kernel/groups.c (ffffffff810a4679)
Location: kernel/groups.c:64
Inline: True
Inline callers:
  - kernel/groups.c:SyS_getgroups
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
In kernel/groups.c (ffffffff810a7d79)
Location: kernel/groups.c:64
Inline: True
Inline callers:
  - kernel/groups.c:SyS_getgroups
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
In kernel/groups.c (ffffffff810add95)
Location: kernel/groups.c:40
Inline: True
Inline callers:
  - kernel/groups.c:SyS_getgroups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa8c5)
Location: kernel/groups.c:41
Inline: True
Inline callers:
  - kernel/groups.c:SyS_getgroups
```
```
In net/core/sock.c (ffffffff817b6d78)
Location: net/core/sock.c:1081
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b15a5)
Location: kernel/groups.c:42
Inline: True
Inline callers:
  - kernel/groups.c:SyS_getgroups
```
```
In net/core/sock.c (ffffffff8182f36a)
Location: net/core/sock.c:1085
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8300)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff818797b9)
Location: net/core/sock.c:1096
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810b8300-ffffffff810b8391: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c13e0)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff8189a3fc)
Location: net/core/sock.c:1081
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810c13e0-ffffffff810c1471: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c74d0)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff818e49f3)
Location: net/core/sock.c:1201
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810c74d0-ffffffff810c755e: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d05a0)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81916bda)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810d05a0-ffffffff810d062e: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da42a)
Location: kernel/groups.c:42
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff819e7e51)
Location: net/core/sock.c:1290
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5b8a)
Location: kernel/groups.c:42
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff819e7918)
Location: net/core/sock.c:1280
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d784a)
Location: kernel/groups.c:37
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff819cd8cd)
Location: net/core/sock.c:1296
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb0fa)
Location: kernel/groups.c:37
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81a7cec6)
Location: net/core/sock.c:1405
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81105fd6)
Location: kernel/groups.c:37
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81bf2d6e)
Location: net/core/sock.c:1527
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bbe6)
Location: kernel/groups.c:37
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81da02d0)
Location: net/core/sock.c:1580
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138a46)
Location: kernel/groups.c:37
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81e0f2b3)
Location: net/core/sock.c:1596
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143616)
Location: kernel/groups.c:37
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81ecbd05)
Location: net/core/sock.c:1577
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010130ce0)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__arm64_sys_getgroups
```
```
In net/core/sock.c (ffff800010baae18)
Location: net/core/sock.c:1203
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffff800010130ce0-ffff800010130ea8: groups_to_user (STB_LOCAL)
ffff800010baae18-ffff800010baafe0: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c03805cc)
Location: kernel/groups.c:42
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_getgroups
```
```
In net/core/sock.c (c0ccd600)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a508)
Location: kernel/groups.c:42
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_getgroups
```
```
In net/core/sock.c (c000000000c859c4)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e416e)
Location: kernel/groups.c:42
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_getgroups
```
```
In net/core/sock.c (ffffffe000741154)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca920)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff818b6bda)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810ca920-ffffffff810ca9ae: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b9130)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81870b2a)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810b9130-ffffffff810b91be: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c9e50)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81907bda)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810c9e50-ffffffff810c9ede: groups_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int groups_to_user(gid_t *grouplist, const struct group_info *group_info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d23a0)
Location: kernel/groups.c:42
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
```
```
In net/core/sock.c (ffffffff81928c0b)
Location: net/core/sock.c:1203
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff810d23a0-ffffffff810d242e: groups_to_user (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
