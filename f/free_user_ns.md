# Function: <code>free_user_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111e3d0)
Location: kernel/user_namespace.c:144
Inline: False
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/super.c:destroy_super
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_setgroups_open
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:remove_notification
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8111e3d0-ffffffff8111e41f: free_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811262f0)
Location: kernel/user_namespace.c:144
Inline: False
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/super.c:destroy_super
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff811262f0-ffffffff8112633f: free_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112fdc0)
Location: kernel/user_namespace.c:181
Inline: False
```
**Symbols:**

```
ffffffff8112fdc0-ffffffff8112fe30: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811313d0)
Location: kernel/user_namespace.c:182
Inline: False
```
**Symbols:**

```
ffffffff811313d0-ffffffff81131440: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113df50)
Location: kernel/user_namespace.c:184
Inline: False
```
**Symbols:**

```
ffffffff8113df50-ffffffff8113e02d: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114c8f0)
Location: kernel/user_namespace.c:184
Inline: False
```
**Symbols:**

```
ffffffff8114c8f0-ffffffff8114c9cd: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81159510)
Location: kernel/user_namespace.c:184
Inline: False
```
**Symbols:**

```
ffffffff81159510-ffffffff811595ed: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81165c50)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff81165c50-ffffffff81165d41: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81171b10)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff81171b10-ffffffff81171c01: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81183930)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff81183930-ffffffff81183a21: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811814b0)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff811814b0-ffffffff811815d5: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811825d0)
Location: kernel/user_namespace.c:181
Inline: False
```
**Symbols:**

```
ffffffff811825d0-ffffffff811826f5: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811aa5a0)
Location: kernel/user_namespace.c:197
Inline: False
```
**Symbols:**

```
ffffffff811aa5a0-ffffffff811aa6c5: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811dbbe0)
Location: kernel/user_namespace.c:202
Inline: False
```
**Symbols:**

```
ffffffff811dbbe0-ffffffff811dbd08: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81221420)
Location: kernel/user_namespace.c:202
Inline: False
```
**Symbols:**

```
ffffffff81221420-ffffffff81221548: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812378d0)
Location: kernel/user_namespace.c:202
Inline: False
```
**Symbols:**

```
ffffffff812378d0-ffffffff812379f8: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81251100)
Location: kernel/user_namespace.c:202
Inline: False
```
**Symbols:**

```
ffffffff81251100-ffffffff81251238: free_user_ns (STB_LOCAL)
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
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e6450)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffff8000101e6450-ffff8000101e655c: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426128)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
c0426128-c0426224: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000255d30)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
c000000000255d30-c000000000255e90: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015b3ca)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffe00015b3ca-ffffffe00015b4ca: free_user_ns (STB_LOCAL)
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
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a130)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff8116a130-ffffffff8116a221: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d330)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff8115d330-ffffffff8115d421: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81167f00)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff81167f00-ffffffff81167ff1: free_user_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_user_ns(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811755a0)
Location: kernel/user_namespace.c:180
Inline: False
```
**Symbols:**

```
ffffffff811755a0-ffffffff81175691: free_user_ns (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct work_struct *work</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *ns</code>
</li>
</ul>
</details>
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
