# Function: <code>locks_translate_pid</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff812d3860)
Location: fs/locks.c:2068
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812d3860-ffffffff812d389f: locks_translate_pid.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff812fdd00)
Location: fs/locks.c:2066
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812fdd00-ffffffff812fdd4b: locks_translate_pid.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81313770)
Location: fs/locks.c:2180
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81313770-ffffffff813137bb: locks_translate_pid.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133b3ca)
Location: fs/locks.c:2198
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8133af80-ffffffff8133afab: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8135393a)
Location: fs/locks.c:2287
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813534e0-ffffffff8135350b: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81399880)
Location: fs/locks.c:2290
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81399880-ffffffff813998cf: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ab360)
Location: fs/locks.c:2291
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813ab360-ffffffff813ab3bf: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b2830)
Location: fs/locks.c:2294
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813b2830-ffffffff813b288f: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81402520)
Location: fs/locks.c:2197
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81402520-ffffffff8140257f: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81476f50)
Location: fs/locks.c:2183
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81476f50-ffffffff81476fc1: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509720)
Location: fs/locks.c:2164
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81509720-ffffffff81509791: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81540ce0)
Location: fs/locks.c:2141
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81540ce0-ffffffff81540d51: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815761c0)
Location: fs/locks.c:2148
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff815761c0-ffffffff81576231: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffff800010415500)
Location: fs/locks.c:2287
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffff800010415028-ffff800010415068: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e21dc)
Location: fs/locks.c:2287
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
c05e21dc-c05e2240: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000524a30)
Location: fs/locks.c:2287
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
c000000000524a30-c000000000524ac8: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
pid_t locks_translate_pid(struct file_lock *fl, struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bcc0a)
Location: fs/locks.c:2287
Inline: True
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffe0002bcc0a-ffffffe0002bcc66: locks_translate_pid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8134bf1a)
Location: fs/locks.c:2287
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8134bac0-ffffffff8134baeb: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133cbfa)
Location: fs/locks.c:2287
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8133c7a0-ffffffff8133c7cb: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff813499ea)
Location: fs/locks.c:2287
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81349590-ffffffff813495bb: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8135d29a)
Location: fs/locks.c:2287
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
Direct callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8135ce30-ffffffff8135ce70: locks_translate_pid.isra.0.part.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
