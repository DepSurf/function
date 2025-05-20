# Function: <code>copy_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8111f8b0)
Location: kernel/pid_namespace.c:153
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8111f8b0-ffffffff8111fc02: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81127800)
Location: kernel/pid_namespace.c:153
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81127800-ffffffff81127b51: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81131470)
Location: kernel/pid_namespace.c:172
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81131470-ffffffff811317e7: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81132a40)
Location: kernel/pid_namespace.c:175
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81132a40-ffffffff81132db2: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8113f840)
Location: kernel/pid_namespace.c:168
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8113f840-ffffffff8113fb4a: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8114e180)
Location: kernel/pid_namespace.c:149
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8114e180-ffffffff8114e442: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8115ae60)
Location: kernel/pid_namespace.c:149
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8115ae60-ffffffff8115b124: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81167510)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81167510-ffffffff811677cf: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811733d0)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811733d0-ffffffff8117368f: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81185520)
Location: kernel/pid_namespace.c:141
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81185520-ffffffff811855b0: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81182620)
Location: kernel/pid_namespace.c:141
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81182620-ffffffff811826b5: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81183770)
Location: kernel/pid_namespace.c:141
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81183770-ffffffff81183816: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811ab850)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811ab850-ffffffff811ab8f6: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811dcfc0)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811dcfc0-ffffffff811dd063: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81222970)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81222970-ffffffff81222a13: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81238fd0)
Location: kernel/pid_namespace.c:145
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81238fd0-ffffffff81239073: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81252ca0)
Location: kernel/pid_namespace.c:146
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81252ca0-ffffffff81252d43: copy_pid_ns (STB_GLOBAL)
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
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffff8000101e76f0)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffff8000101e76f0-ffff8000101e79a4: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (c0427ad4)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
c0427ad4-c0427d7c: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (c000000000257f90)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
c000000000257f90-c000000000258318: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffe00015cbfc)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffe00015cbfc-ffffffe00015ce0c: copy_pid_ns (STB_GLOBAL)
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
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8116b9f0)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8116b9f0-ffffffff8116bcaf: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8115ebf0)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8115ebf0-ffffffff8115eeaf: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811697c0)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811697c0-ffffffff81169a7f: copy_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid_namespace *copy_pid_ns(long unsigned int flags, struct user_namespace *user_ns, struct pid_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81176ee0)
Location: kernel/pid_namespace.c:150
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81176ee0-ffffffff8117719f: copy_pid_ns (STB_GLOBAL)
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
