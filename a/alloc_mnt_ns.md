# Function: <code>alloc_mnt_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b6a0)
Location: fs/namespace.c:2753
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff8122b6a0-ffffffff8122b777: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81253e10)
Location: fs/namespace.c:2740
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff81253e10-ffffffff81253ee7: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812670f0)
Location: fs/namespace.c:2870
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff812670f0-ffffffff8126722f: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274940)
Location: fs/namespace.c:2812
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff81274940-ffffffff81274a86: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297270)
Location: fs/namespace.c:2885
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff81297270-ffffffff812973b6: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd460)
Location: fs/namespace.c:2916
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff812bd460-ffffffff812bd5a6: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2770)
Location: fs/namespace.c:2888
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff812d2770-ffffffff812d28b6: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef970)
Location: fs/namespace.c:3155
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812ef970-ffffffff812efa9f: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301440)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81301440-ffffffff8130156f: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ab00)
Location: fs/namespace.c:3244
Inline: False
Direct callers:
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8133ab00-ffffffff8133ac3c: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346d10)
Location: fs/namespace.c:3266
Inline: False
Direct callers:
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff81346d10-ffffffff81346e86: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134d210)
Location: fs/namespace.c:3299
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8134d210-ffffffff8134d386: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139b1e0)
Location: fs/namespace.c:3373
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8139b1e0-ffffffff8139b356: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141ea40)
Location: fs/namespace.c:3416
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8141ea40-ffffffff8141ebbb: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ab4b0)
Location: fs/namespace.c:3521
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff814ab4b0-ffffffff814ab62b: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e02b0)
Location: fs/namespace.c:3708
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff814e02b0-ffffffff814e042b: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81513580)
Location: fs/namespace.c:3725
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81513580-ffffffff815136ec: alloc_mnt_ns (STB_LOCAL)
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
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4c20)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffff8000103b4c20-ffff8000103b4d90: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592940)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
c0592940-c0592aa8: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0b10)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
c0000000004b0b10-c0000000004b0cc4: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027737e)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffe00027737e-ffffffe00027748a: alloc_mnt_ns (STB_LOCAL)
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
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9a20)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812f9a20-ffffffff812f9b4f: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea640)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812ea640-ffffffff812ea76f: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7810)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812f7810-ffffffff812f793f: alloc_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mnt_namespace *alloc_mnt_ns(struct user_namespace *user_ns, bool anon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308b20)
Location: fs/namespace.c:3186
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81308b20-ffffffff81308c4f: alloc_mnt_ns (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool anon</code>
</li>
</ul>
</details>
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
