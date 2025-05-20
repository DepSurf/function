# Function: <code>copy_cgroup_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81119a30)
Location: kernel/cgroup.c:5986
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81119a30-ffffffff81119b5d: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121850)
Location: kernel/cgroup.c:6352
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81121850-ffffffff8112196e: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129df0)
Location: kernel/cgroup.c:6392
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81129df0-ffffffff81129f49: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81128e00)
Location: kernel/cgroup/namespace.c:49
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81128e00-ffffffff81128fa0: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81135a80)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81135a80-ffffffff81135c12: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81144390)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81144390-ffffffff8114452f: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8114fea0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8114fea0-ffffffff8115003f: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8115bda0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8115bda0-ffffffff8115bf3a: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff811679c0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811679c0-ffffffff81167b5a: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff811792e0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811792e0-ffffffff811794ea: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81175ff0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81175ff0-ffffffff81176257: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81176b70)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81176b70-ffffffff81176dbf: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8119e3f0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8119e3f0-ffffffff8119e63f: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff811ce820)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811ce820-ffffffff811cea62: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff812120a0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff812120a0-ffffffff812122e2: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81227a00)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81227a00-ffffffff81227c49: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8123f810)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8123f810-ffffffff8123fa59: copy_cgroup_ns (STB_GLOBAL)
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
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffff8000101da290)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffff8000101da290-ffff8000101da4e8: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (c041cb08)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
c041cb08-c041ccc4: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (c0000000002474b0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
c0000000002474b0-c000000000247770: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffe00015299e)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffe00015299e-ffffffe000152b36: copy_cgroup_ns (STB_GLOBAL)
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
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8115ffe0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8115ffe0-ffffffff8116017a: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81153250)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81153250-ffffffff811533e4: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8115ddb0)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8115ddb0-ffffffff8115df4a: copy_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_namespace *copy_cgroup_ns(long unsigned int flags, struct user_namespace *user_ns, struct cgroup_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8116b020)
Location: kernel/cgroup/namespace.c:50
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8116b020-ffffffff8116b1b5: copy_cgroup_ns (STB_GLOBAL)
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
