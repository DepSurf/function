# Function: <code>copy_time_ns</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81159f90)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81159f90-ffffffff81159ff8: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81155ee0)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81155ee0-ffffffff81155f47: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81157180)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81157180-ffffffff8115734c: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8117bfd0)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8117bfd0-ffffffff8117c19c: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811b1720)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811b1720-ffffffff811b1910: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f2470)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff811f2470-ffffffff811f2660: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81206bf0)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff81206bf0-ffffffff81206de0: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct time_namespace *copy_time_ns(long unsigned int flags, struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121de00)
Location: kernel/time/namespace.c:133
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
```
**Symbols:**

```
ffffffff8121de00-ffffffff8121dff0: copy_time_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
