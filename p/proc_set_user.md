# Function: <code>proc_set_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127ebf0)
Location: fs/proc/generic.c:524
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
**Symbols:**

```
ffffffff8127ebf0-ffffffff8127ec01: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812abdbd)
Location: fs/proc/generic.c:529
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
**Symbols:**

```
ffffffff812abc10-ffffffff812abc21: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c18cc)
Location: fs/proc/generic.c:531
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff812c14e0-ffffffff812c14f1: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ced95)
Location: fs/proc/generic.c:515
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff812ce880-ffffffff812ce891: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3571)
Location: fs/proc/generic.c:525
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff812f3050-ffffffff812f3061: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320408)
Location: fs/proc/generic.c:634
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8131ff60-ffffffff8131ff71: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813374ef)
Location: fs/proc/generic.c:636
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81337040-ffffffff81337051: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f622)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8135f170-ffffffff8135f181: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377882)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813773d0-ffffffff813773e1: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c06f2)
Location: fs/proc/generic.c:650
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813c0130-ffffffff813c0141: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2542)
Location: fs/proc/generic.c:670
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813d1fa0-ffffffff813d1fb1: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9342)
Location: fs/proc/generic.c:665
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff813d8e80-ffffffff813d8e91: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142aa72)
Location: fs/proc/generic.c:665
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8142a5b0-ffffffff8142a5c1: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4048)
Location: fs/proc/generic.c:668
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff814a3b50-ffffffff814a3b6b: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539458)
Location: fs/proc/generic.c:668
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81538ec0-ffffffff81538edb: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571698)
Location: fs/proc/generic.c:667
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81571110-ffffffff8157112b: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa048)
Location: fs/proc/generic.c:667
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff815a9ab0-ffffffff815a9acb: proc_set_user (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff8000104434fc)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffff800010442f08-ffff800010442f40: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c060886c)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
c0608330-c0608350: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558bb4)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
c000000000558420-c000000000558434: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002d9c0c)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffe0002d96c2-ffffffe0002d96f6: proc_set_user (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136fe62)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff8136f9b0-ffffffff8136f9c1: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813608f2)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81360440-ffffffff81360451: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136d932)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_init
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_init
```
**Symbols:**

```
ffffffff8136d480-ffffffff8136d491: proc_set_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void proc_set_user(struct proc_dir_entry *de, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381265)
Location: fs/proc/generic.c:637
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_notify_change
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
**Symbols:**

```
ffffffff81380db0-ffffffff81380dc1: proc_set_user (STB_GLOBAL)
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
